在61服务器`bolt://localhost:7688`上启动了neo4j服务，应该可以使用我给出的代码连接（jupyter里面有）

```python
from py2neo import Graph
uri = "bolt://localhost:7688"
username = "neo4j"
password = "ainet666"
graph = Graph(uri, auth=(username, password))
```