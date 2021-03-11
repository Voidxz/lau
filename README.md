# Lau
Lau is a much better version of Lua, here is some example code!

```
locale variable = 'hello world'

locale perform printer(...)
	print(...)
stop

_G.print = ~/(...)io.write(table.concat([...], '\t') .. '\n')~|

printer(variable, 'ae')
```