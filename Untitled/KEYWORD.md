# Hindi Study
```aosr-deck-config
{
	"rule":{
		"conditions":{
			"not":
				{
					"fact":"card",
					"operator":"regexMatch",           
					"value":"Untitled 11.md",  
					"path":"$.path"
				}
		},
		"event":{
			"type":"match"
		}
	}
}
```