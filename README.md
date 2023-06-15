# 随机题头图

随机题头图，点击当前文档空白处，再点击顶栏右上角图标选择类型。

## 添加新的图源

找到```工作空间/data/storage/petal/siyuan-plugin-more-background/settings```文件，使用记事本打开，按照JSON格式，添加label和url即可。
label的值是对应图源在插件菜单中的选项文本


例：
原版：
```
[{"label":"ACG","url":"https://img.xjh.me/random_img.php?return=302"}]
```


```
[
{"label":"ACG","url":"https://img.xjh.me/random_img.php?return=302"},
{"label":"自己命名","url":"http://www.98qy.com/sjbz/api.php?return=302"}
]
```


注意：
* URL必须是能够直接返回图片的形式，最好是302重定向方式获取的
* 除最后一行图源的}后面不需要```,```以外，上面部分的}后面皆需要```，```
