# return-killer-PopClip-Extension

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
