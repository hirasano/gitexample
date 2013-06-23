## Gitを勉強する


## 1. ローカルリポジトリを作成する
```
$ mkdir ~/gitexample
$ git init
Initialized empty Git repository in ~/gitexample/.git/
```
*master*というローカルリポジトリ上のブランチにいる状態になる

## 2. コミットする
```
$ vim README.md
$ git add README.md
$ git commit -m "Initial Commit" README.md
```

## 3. リモートリポジトリとしてGitHub上にリポジトリを作成する

## 4. リモートリポジトリを加える
```
$ git remote add origin https://github.com/hirasano/gitexample.git
```

## 5. リモートリポジトリにpushする
```
$ git push origin master
```
*origin* (=GitHub)上の *master* ブランチに *master*(ローカルリポジトリ) の作業内容をpushする
