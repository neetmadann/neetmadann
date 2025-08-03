# 👋 Hi, I'm Neet

I'm a Data Scientist with a background in Business Intelligence.  
I love turning data into insights and dashboards into stories.

---

## 🛠️ My Toolbox

- Python, R, SQL, DAX  
- SVG, Deneb, learning D3.js

---

## 📦 Most Used Languages

```python
# Python: List your most-used languages via GitHub API
from github import Github

g = Github("YOUR_GITHUB_TOKEN")
user = g.get_user("neetmadann")
lang_count = {}
for repo in user.get_repos():
    for lang, count in repo.get_languages().items():
        lang_count[lang] = lang_count.get(lang, 0) + count
print(sorted(lang_count.items(), key=lambda x: x[1], reverse=True))
```

---

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=neetmadann&show_icons=true&theme=tokyonight)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=neetmadann&layout=compact&theme=tokyonight)
