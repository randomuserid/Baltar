File & Object Access events - these are the events produced by file and object access auditing that are needed to hunt suspicious file and print activity.
Enable such auditing with care because this tends to produce some of the largest event data volumes.

| EventID | Description                                                                            |
|---------|----------------------------------------------------------------------------------------|
| 4656    | A handle to an object was requested.                                                   |
| 4658    | The handle to an object was closed.                                                    |
| 4659    | A handle to an object was requested with intent to delete.                             |
| 4660    | An object was deleted                                                                  |
| 4663    | An attempt was made to access an object.                                               |
| 4664    | An attempt was made to create a hard link.                                             |
| 4685    | The state of a transaction has changed                                                 |
| 4691    | Indirect access to an object was requested.                                            |
| 4985    | The state of a transaction has changed                                                 |
| 5140    | A network share object was accessed                                                    |
| 5142    | share added                                                                            |
| 5143    | share modified                                                                         |
| 5144    | share deleted                                                                          |
| 5145    | A network share object was checked to see whether client can be granted desired access |
