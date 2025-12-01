```aosr-deck-config
{
	"rule": {
		"conditions": {
			"all": [{
				"fact": "card",
				"operator": "regexMatch",
				"value": "",    <--  Replace with your own note path keyword
				"path": "$.path"
			}]
		},
		"event": {
			"type": "match"
		}
	}
}
```