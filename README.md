# Importer
用于跨维基导入页面的拓展
#Usage
```php
//该函数用于跨维基导入页面,是API:action=import的变通方法
//使用前,请确保至少登陆目标维基
//$fromwiki:指定了来源维基
//$targetwiki:指定了目标维基
//$fromtitle:指定了来源页面名称
//$targetwiki:指定了目标页面名称
//$summary:指定了编辑摘要(留空则填写缺省摘要)
ext_import($fromwiki,$targetwiki,$fromtitle,$targettitle,$summary=""){
```
