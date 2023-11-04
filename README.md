
# 主要參考：
[ref](https://www.netlify.com/blog/2015/12/08/a-step-by-step-guide-gitbook-on-netlify/)


# 前言：

- 這邊是用 node 自己在 local 建設

- 不想要用 gitbook 官方釋出的，Web Gui 做綁定
只是一個紀錄歷程不用那麼浩大。


# 安裝和啟動

```
確認一下你本機的 node -v, 尤其是每次終端機重開
nvm install v12.16.3 / nvm use v12.16.3

npm install -g gitbook-cli --save-dev

gitbook init

gitbook serve
or
gitbook serve --port 8081

```

# ref: 

- why v12.16.3: [link](https://www.cnblogs.com/hacv/p/14311409.html)

- 目錄的寫法： [link](https://frankbing.gitbooks.io/gitbook/content/part3_3.html)

- gitbook-cli: [link](https://github.com/GitbookIO/gitbook-cli)

# 其他：

- 研究一下插件