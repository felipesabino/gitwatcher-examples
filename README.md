Examples of git-watcher usage
====================

Add `gitwatcher` dependency to your package.json `devDependencies` section and then the following code to the `before_script` section of yout `.travis.yml` file

```
- ./node_modules/.bin/git-watcher-files --commit $TRAVIS_COMMIT_RANGE
```
