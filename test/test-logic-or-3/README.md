# prog
## Human
```

```
## Source
```lisp
( print ( | 0 0 0 ) ( | 0 0 1 ) ( | 0 1 0 ) ( | 0 1 1 ) ( | 1 0 0 ) ( | 1 0 1 ) ( | 1 1 0 ) ( | 1 1 1 ) )
```
## Token Stream
```json
{"separator":"("}
{"identifier":"print"}
{"separator":"("}
{"identifier":"|"}
{"identifier":"0"}
{"identifier":"0"}
{"identifier":"0"}
{"separator":")"}
{"separator":"("}
{"identifier":"|"}
{"identifier":"0"}
{"identifier":"0"}
{"identifier":"1"}
{"separator":")"}
{"separator":"("}
{"identifier":"|"}
{"identifier":"0"}
{"identifier":"1"}
{"identifier":"0"}
{"separator":")"}
{"separator":"("}
{"identifier":"|"}
{"identifier":"0"}
{"identifier":"1"}
{"identifier":"1"}
{"separator":")"}
{"separator":"("}
{"identifier":"|"}
{"identifier":"1"}
{"identifier":"0"}
{"identifier":"0"}
{"separator":")"}
{"separator":"("}
{"identifier":"|"}
{"identifier":"1"}
{"identifier":"0"}
{"identifier":"1"}
{"separator":")"}
{"separator":"("}
{"identifier":"|"}
{"identifier":"1"}
{"identifier":"1"}
{"identifier":"0"}
{"separator":")"}
{"separator":"("}
{"identifier":"|"}
{"identifier":"1"}
{"identifier":"1"}
{"identifier":"1"}
{"separator":")"}
{"separator":")"}
```
## Abstract syntax tree
```json
[ "print", [ "|", "0", "0", "0" ], [ "|", "0", "0", "1" ], [ "|", "0", "1", "0" ], [ "|", "0", "1", "1" ], [ "|", "1", "0", "0" ], [ "|", "1", "0", "1" ], [ "|", "1", "1", "0" ], [ "|", "1", "1", "1" ] ]
```
## Interpreter
```bash
false
true
true
true
true
true
true
true
```