## Table of Content 
- [key](#key)
- [sleep](#sleep)
- [lua](#lua)
- [print](#print)
- [click](#click)
- [return](#return)

### [◄ Acc Script](AccScript.md)

## key
```
void key("key")
```

Press `key`

`key` example: Ctrl+Shift+1, F1, Super+D

## sleep
```
void sleep(value)
```

Sleep `value` in miliseconds

## lua
```
void lua("script_path")
```

Run lua from `script_path`

## print
```
void print("value")
```

Print `value` in debug console

## click
```
void click("acc_path", "action", "name", offset_x, offset_y, offset_id)
```

Do an `action` on center of `acc_path`

** <action\> **
	
Possible actions are 

- `L`: Left Click
- `R`: Right Click
- `M`: Middle Click
- `D`: Double Click
- `C`: Report Child ID (Debug Action)
	
**<name\>** `optional`

Specify a child in a list
	
**<offset_x, offset_y\>** `optional`

Add offset to the click position
	
**<offset_id\>** `optional`

Add offset to final child Id

## return
```
return
```

Return from the app.