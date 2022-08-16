# heroku-joplin
Dockerfile中镜像，是打包的官方存储库fork过来的，通过GitHub Actions自动生成镜像到hub.docker.com

# app.json
##自动生成仓库地址，环境
https://dashboard.heroku.com/new?template=https%3A%2F%2Fgithub.com%2Fzuikea%2Fheroku-joplin%2Fblob%2Fmain
## app.json含义
https://devcenter.heroku.com/articles/setting-up-apps-using-the-heroku-platform-api
https://devcenter.heroku.com/articles/app-json-schema
# heroku.yml
通过这个文件指明Dockerfile构建仓库
