# heroku-joplin
Dockerfile中镜像，是打包的官方存储库fork过来的，通过GitHub Actions自动生成镜像到hub.docker.com

# app.json
自动生成heroku环境  

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/zuikea/heroku-joplin)

## app.json含义
https://devcenter.heroku.com/articles/setting-up-apps-using-the-heroku-platform-api
https://devcenter.heroku.com/articles/app-json-schema
# heroku.yml
通过这个文件指明Dockerfile构建仓库
