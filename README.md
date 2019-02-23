[![](https://img.shields.io/pypi/pyversions/github-remote.svg?longCache=True)](https://pypi.org/project/github-remote/)
[![](https://img.shields.io/pypi/v/github-remote.svg?maxAge=3600)](https://pypi.org/project/github-remote/)
[![Travis](https://api.travis-ci.org/looking-for-a-job/github-remote.py.svg?branch=master)](https://travis-ci.org/looking-for-a-job/github-remote.py/)

#### Install
```bash
$ [sudo] pip install github-remote
```

#### Functions
function|`__doc__`
-|-
`github_remote.add(name, url)`|`git remote add name url`
`github_remote.get()`|return git remote tuple (name, url)
`github_remote.name()`|return git remote name
`github_remote.rm()`|`git remote rm name`
`github_remote.url()`|return git remote url

#### CLI
usage|`__doc__`
-|-
`python -m github_remote.name`|print git remote name
`python -m github_remote.rm`|`git remote rm name`
`python -m github_remote.url`|print git remote url

<p align="center"><a href="https://pypi.org/project/readme-md/">readme-md</a> - README.md generator</p>