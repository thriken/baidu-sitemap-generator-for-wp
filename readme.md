
![](https://img.shields.io/github/v/release/thriken/baidu-sitemap-generator-for-wp)

[DownLoad](https://github.com/thriken/baidu-sitemap-generator-for-wp)

===Baidu Sitemap Generator===

Contributors: thriken,柳城

Tags: Baidu,XML,Sitemap

Requires at least: 2.7

Tested up to: 3.80

Stable tag: trunk


Baidu Sitemap Generator

== Description ==

This pulgin generates a Baidu XML-Sitemap for WordPress Blog. Also Build a real Static Sitemap-Page for all Search Engine. | 生成百度 Sitemap XML 文件。就相当于网站被百度--全球最大的中文搜索引擎订阅，进而为您的网站带来潜在的流量。同时生成一个静态的站点地图页面，对所有的搜索引擎都有利。兼容PHP7.4+，wordpress6.9已测试通过。


Related Links:
* <a href="https://blog.elec.top/baidu-sitemap-generator.html">Report a BUG</a>  
* <a href="http://liucheng.name/2113/">原作者链接</a>
* <a href="http://zhanzhang.baidu.com/">百度站长平台</a>

v2.0.3 2026-5-26
1. baidu_sitemao.php 第220行 一个过时的语法 ，get_all_category_ids() 修改为 get_terms()

v2.0.2 2026-5-15
1. 修复一个语法不严谨
    问题在baidu_sitemap.php第420行：$get_baidu_sitemap_options 可能是字符串而非数组。
    需要添加类型检查：
    添加了 is_array() 和 isset() 检查，确保 $get_baidu_sitemap_options 是数组且包含该键时才访问。



V2.0.1
1. 修复了一个已弃用的方法  add_options_page('插件名称', '插件名称', 8, basename(__FILE__), 'my_options_page');   8->'manage_options'
2. 语法升级到PHP7.4+


V1.50
1，修复常见的BUG
2，优化SAE环境
3. 支持wordpress3.80版本


V1.44 ~ v1.46

1，修复频繁更新的BUG

2, 支持SAE环境

3，修复与其它插件有冲突的BUG

4, 插件冲突（1.45）

5, URL存在"&"等特殊符号时引起的BUG（1.46）


V1.43

1，修复几个小BUG

V1.40

1，支持百度站长平台Sitemap
2, 增加目录及Page页面

V 1.31

1，提醒百度ping服务的地址
2，提醒百度站长平台
3，欢迎大家的意见


V 1.20

1，解决更新时没有生成最新文章的BUG
2，解决win下"权限问题"的错误提示（有待测试）
3，解决没有评论不显示的问题



== Screenshots ==

1. Baidu Sitemap admin panel


== Installation ==

(1) unzip the baidu-sitemap-generator.zip file in /wp-content/plugins

(2) Active the plugin 

Baidu—Sitemap-Generator for WordPress


== Translations ==

此插件支持多语言，含有语言包模版。欢迎您来翻译。

The plugin comes with various translations, please refer to the [WordPress Codex](http://codex.wordpress.org/Installing_WordPress_in_Your_Language "Installing WordPress in Your Language") for more information about activating the translation. If you want to help to translate the plugin to your language, please have a look at the sitemap.pot file which contains all defintions and may be used with a [gettext](http://www.gnu.org/software/gettext/) editor like [Poedit](http://www.poedit.net/) (Windows).


