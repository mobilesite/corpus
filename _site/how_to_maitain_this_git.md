# 管理这个git项目的备忘录

## 新建此项目

mkdir corpus

cd corpus

git init

git checkout --orphan gh-pages

git add .

git commit -m 'first commit'

git remote add origin https://github.com/mobilesite/corpus.git

git push origin gh-pages

## 协作

git clone https://github.com/mobilesite/corpus.git

git checkout gh-pages

git config user.name xxx

git config user.email xxx@xxx.xxx.xxx

git add .

git commit -m 'update'

git push origin gh-pages



