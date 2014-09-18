Examples of git-watcher usage
====================

Add the following lines to the `before_install` section of your `.travis.yml`

```
- git clone https://github.com/felipesabino/gitwatcher
- cd gitwatcher
- npm install
- npm link
- cd ..
- git-watcher-files --commit $TRAVIS_COMMIT_RANGE
```
