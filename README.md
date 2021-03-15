# Simple fork from [degoogle](https://github.com/deepseagirl/degoogle) with bug hunting purposes  based on [degoogle_hunter](https://github.com/six2dez/degoogle_hunter)

> You can add dorks as follows:

```
(TITLE)(LEVEL)<DORK [DOMAIN]>
```
**NOTE: if you want to reference a target in the idiot, you need to put [DOMAIN]**
Save the dork in the dorks file you will use.

Example:
```
(jenkins)(info)<intitle:\"Dashboard [Jenkins]\" \"[DOMAIN]\">
```

# How to

```
git clone https://github.com/six2dez/degoogle_hunter
cd degoogle_hunter 
python3 degoogle.py -fd dorks.txt -d target.com
```
