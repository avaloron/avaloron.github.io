# Avaloron 雅闻隆官方网站

# 投稿流程

* 注册github账号
* fork 网站源代码，
* 在自己的fork代码仓里的`_posts/`文件夹内新建markdown文档(也可以复制`_posts/template/yyyy-mm-dd-Your-Article-Title.markdown`一份到`_posts/`下)，并参照已有的文件格式创作内容
* 提交pull request, @ 相关编辑来审稿
* 通过审核后，你的文章便收录在Avaloron的官方网站了。

# 网站开发流程 development

开发安装常规流程: Make a pull request to the master branch directly.

### system requirement
* ruby 2.1+

### install dependences
First, change your current working directory to the root directory of this source code.

```
gem install nokogiri -v '1.8.0' # if you haven't done so
# for mac configuration
# bundle config build.nokogiri --use-system-libraries
gem install bundler # if you haven't got bundler installed
bundle install
```
### bring up your local web
```
bundle exec jekyll server
```
### preview all your changes (debug) locally

open local web browser (i.e. Chrome, Safari and Firefox, etc.)

insert "http://localhost:4000/" to the browser

# 版权

每位作者保留自己作品的所有版权
all copyright reserved
