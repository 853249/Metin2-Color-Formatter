
# Metin2-Color-Formatter
A simple class which convert the values into a string by a specific color name.
Python Color Constants Module:
	
	https://www.webucator.com/blog/2015/03/python-color-constants-module/
	https://www.color-hex.com/color/ccffff

Ex-How-To-Use:

```py
text = CFF.format('Metin2', 'green')
text = CFF.format(8000, 'banana')
text = CFF.format(412.55, 'red')
text = CFF.format('Pending', '#113355')
text = CFF.format('Item name:', 'springgreen', CFF.FLAG_NEW_TAB) + CFF.format(item.GetItemName(), 'chocolate')
text = CFF.multi_format(('a', 'b', 'c'), 'red') # text[0], text[1], text[2]
```
