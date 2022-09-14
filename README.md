# Degoogle
> Simple fork from [degoogle](https://github.com/deepseagirl/degoogle) with bug hunting purposes  based on [degoogle_hunter](https://github.com/six2dez/degoogle_hunter)

> You can add dorks as follows:

```
{"name":"NAME","severity":"SEVERITY","query":"DORK QUERY"}
```
**NOTE: if you want to reference a target in the dork, you need to put [DOMAIN]**

Save the dork in the dorks file you will use.

Example:
```
{"name": "apache_struts_rce", "severity": "high", "query": "site:[DOMAIN] ext:action | ext:struts | ext:do"}
```

# How to

```
git clone https://github.com/phor3nsic/degoogle.git
cd degoogle 
python3 degoogle.py -fd dorks.json -d target.com
```
