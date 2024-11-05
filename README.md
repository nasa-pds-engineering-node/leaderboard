# 🏆 Leaderboard


## 📝 Notes

-   [PR](https://github.com/NASA-AMMOS/slim-leaderboard/pull/5) to make `slim-leaderboard` `pip install`-able is open at this time
    -   So must `pip install` with `--index-url` of https://test.pypi.org/simple/
    -   But it has dependencies on plain PyPI, so `--extra-index-url` https://pypi.org/simple/

By hand:
```
python3 -m venv .venv
. .venv/bin/activate
pip install slim-leaderboard
env GITHUB_TOKEN=ghp_[READACTED] slim-leaderboard --emoji --output_format MARKDOWN engineering.json > index.md
```

