# wkhtmltopdf for Mac

## 背景
* 最近一朋友让我协助解决一个问题，将word文档转成pdf文档
事实上，这个是可以通过PhpWord这个包来完成的，但是在其中有个需求是，
将word模板文件中的一些文字替换为最终的值，做到最后，发现如果使用dompdf包来完成时，
对英文的文档是ok的，但是遇到中文就会乱码，在laravel的论坛中，发现了使用这个 https://github.com/barryvdh/laravel-snappy，
可以解决这个问题
* 这个软件包有个以依赖：wkhtmltopdf
* laravel-snappy 包中提示可以去https://github.com/KnpLabs/snappy#wkhtmltopdf-binary-as-composer-dependencies，
直接使用composer直接安装这个依赖，但这个包是支持debian操作系统的，我本地是mac环境
* 为了解决这个依赖问题，只能去它的官网下载对应的版本：https://wkhtmltopdf.org
* 在github上查看，还有一个仓库是有centos版本的，但找不到mac版本，于是我决定开一个仓库
用于存放mac版本的，便于其他人使用composer安装wkhtmltopdf的mac版本

## 安装
* git clone 
