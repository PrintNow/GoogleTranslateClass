# for free Google Translate|免费的 Google Translate（谷歌翻译）类
> Base on https://github.com/statickidz/php-google-translate-free develop

> 第一次使用 GitHub 客户端提交，LICENSE 有点问题，需要更改.

# Usage|用法
```php
<?php
require_once('./google.translate.class.php');
$trans = new GoogleTranslate();

//This message can capture package `translate.google.com ` get
//这些信息都可以抓 `translate.google.com ` 获取
$source = 'zh-CN';//Source language, 源语言
$target = 'en';//Target language, 目标语言

$text = '好的，谷歌！';

//if $type='cn' use 'translate.google.cn' API elseif $type='intl' use 'translate.google.com' API
//default use 'translate.google.com' API
$result = $trans->translate($source, $target, $text, $type='cn');
//run result 'Ok, Google!'
//运行结果 'Ok, Google!'
```
# LICENSE|执照

## GNU General Public License v3.0
