## IDAPro cheatsheet zh

https://www.hex-rays.com/wp-content/static/products/ida/idapro_cheatsheet.html

replace，剩下的手动替换
```
<td>(\w+\+\w+|\w)</td>

<td><code>$1</code></td>
```

google翻译后，删除所有font
```
<font.*?>(.*)*</font>

$1
```