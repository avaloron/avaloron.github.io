# Avaloron 雅闻隆官方网站

# 投稿流程

* 注册github账号
* fork 网站源代码，
* 在自己的fork代码仓里的`_posts/`文件夹内新建markdown文档(也可以复制`_posts/template/yyyy-mm-dd-Your-Article-Title.markdown`一份到`_posts/`下)，并参照已有的文件格式创作内容
* 提交pull request, @ 相关编辑来审稿
* 通过审核后，你的文章便收录在Avaloron的官方网站了。

# 网站开发流程 development

网站开发请在dev分支内进行，我们会定期merge稳定版本到master

### system requirement
* ruby 2.0+

### install dependences
```
gem install bundler # if you haven't done so
bundle install
```
### bring up your local web 
```
bundle exec jekyll server
```
# 版权

每位作者保留自己作品的所有版权
all copyright reserved
