Examples of git-watcher usage
====================

Add the following code to the `before_install` section of yout `.travis.yml` file

```
- npm install -g gitwatcher
- git-watcher-files --commit $TRAVIS_COMMIT_RANGE
```
