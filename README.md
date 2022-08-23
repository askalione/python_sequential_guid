# Sequential GUID

```python
from sequential_guid import SequentialGuid

# PostgreSQL, MySQL
guid = SequentialGuid.NewGuid(SequentialGuid.STRING)

# MS SQL Server
guid = SequentialGuid.NewGuid(SequentialGuid.ENDING)
```