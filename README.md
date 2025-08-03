## Hi there 👋

<!--
**neetmadann/neetmadann** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on PowerBI Deneb and SVG Custom Visuals
- 🌱 I’m currently learning D3 and Javascript
- 👯 I’m looking to collaborate on Power BI and Python ML 
- 🤔 I’m looking for help with: D3
- 💬 Ask me about Power BI, DAX and Custom visuals
- 📫 How to reach me: https://www.linkedin.com/in/neetmadan/
- ⚡ Fun fact: ...

```python
# Python code to list most-used languages via GitHub API
from github import Github

g = Github("YOUR_GITHUB_TOKEN")
user = g.get_user("neetmadann")
lang_count = {}
for repo in user.get_repos():
    for lang, count in repo.get_languages().items():
        lang_count[lang] = lang_count.get(lang, 0) + count
print(sorted(lang_count.items(), key=lambda x: x[1], reverse=True))
```
