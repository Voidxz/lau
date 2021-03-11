# Lau

example
```
locale variable = 'hello world'

locale perform printer(...)
	print(...)
stop

_G.print = ~/(...)io.write(table.concat([...], '\t') .. '\n')~|

printer(variable, 'ae')
```
