# prog
## Human
```

```
## Source
```lisp
( write ( < 0 0 ) ( < 0 1 ) ( < 0 -1 ) ( < 1 0 ) ( < -1 0 ) ( < 1 1 ) ( < -1 -1 ) )
```
## Token Stream
```json
{"separator":"("}
{"identifier":"write"}
{"separator":"("}
{"identifier":"<"}
{"identifier":0}
{"identifier":0}
{"separator":")"}
{"separator":"("}
{"identifier":"<"}
{"identifier":0}
{"identifier":1}
{"separator":")"}
{"separator":"("}
{"identifier":"<"}
{"identifier":0}
{"identifier":"-1"}
{"separator":")"}
{"separator":"("}
{"identifier":"<"}
{"identifier":1}
{"identifier":0}
{"separator":")"}
{"separator":"("}
{"identifier":"<"}
{"identifier":"-1"}
{"identifier":0}
{"separator":")"}
{"separator":"("}
{"identifier":"<"}
{"identifier":1}
{"identifier":1}
{"separator":")"}
{"separator":"("}
{"identifier":"<"}
{"identifier":"-1"}
{"identifier":"-1"}
{"separator":")"}
{"separator":")"}
```
## Abstract syntax tree
```json
[ "write", [ "<", 0, 0 ], [ "<", 0, 1 ], [ "<", 0, "-1" ], [ "<", 1, 0 ], [ "<", "-1", 0 ], [ "<", 1, 1 ], [ "<", "-1", "-1" ] ]

```
## Interpreter
```bash
false
true
false
false
false
false
false
```