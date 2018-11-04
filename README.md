中文翻译版：（如果需要原版请点击->[show jhipster's README](https://github.com/jhipster/jhipster.github.io/blob/master/README.md)）
这是 JHipster 的公共 [页面](https://www.jhipster.tech/)源码。
=======

这个网页是通过 GitHub pages 呈现的。

本地运行：

* [Fork 本库](https://github.com/jhipster/jhipster.github.io/fork) 并拷贝到你的文件系统。
* [Install Jekyll](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)
* 运行 `bundle install` ，如果你是第一次运行。
 * 如果要避免安装到系统目录，请安装到vendor目录： `bundle install --path vendor/bundle`
 * 在 MacOS 系统中, 如果你在安装 `nokogiri` 有问题, 请尝试: `bundle config build.nokogiri --use-system-libraries=true --with-xml2-include="$(xcrun --show-sdk-path)"/usr/include/libxml2`
* 在克隆的本地项目目录下运行： `bundle exec jekyll serve`。
* 你将能通过这个地址： http://localhost:4000 访问本地版JHipster公共页面。

或者通过 Docker 和 Docker-Compose (Windows 上推荐的方式)

* [Fork 本库](https://github.com/jhipster/jhipster.github.io/fork) 并拷贝到你的文件系统。
* 运行 `docker-compose up`
* 你就能够通过这个地址： http://0.0.0.0:4000 访问到本地版JHipster公共页面。
