# return-killer-PopClip-Extension

删除所有引号、空格、回车和 Tab

```
# popclip return kill
name: ReturnKiller
icon: iconify:grommet-icons:return
javascript: |
  var str = popclip.input.text;
  var newStr = str.replace(/[\s"']/g, '');
  return newStr
after: copy-result
```
