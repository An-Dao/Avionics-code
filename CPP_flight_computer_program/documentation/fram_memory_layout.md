| Address | Data Stored | Interpretation |  Access type | 
| --- | --- |---|---|
| 0x0 | 0 or 1 | 1 => fram full, 0 => has space for >1 memory chunks | RESERVED |
| 0x1 | 0 - 255 | Program State Status Codes | RESERVED |



# Program State Status Codes
| Code | Interpretation |
|---|---|
| 0 | setup() |
| 1 | health checks failed |
| 2 | health checks passed |
| 3 | void loop() |