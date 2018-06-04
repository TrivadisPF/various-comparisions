# Big Data Serialization


|   | CSV/Text | XML   | JSON | Avro | Protocol Buffers | Parquet |
|:------------- |:---------------|:---------------|:-------------|:-------------|:-------------|:-------------|
|              |      |         |            |               |
| Can be used in transit/in motion  | yes        | yes        | yes           | yes              | yes | no |
| Can be persisted   | yes        | yes        | yes           | yes              | yes | yes |
| SerDe directly suppports compression | no        |  no       |  no          |  yes             | ? | ? |
| Row Format | yes        |  yes       |  yes          |  yes             | yes | no |
| Columnar Format | no        |  no       |  no          |  no             | no | yes |
| Support for Data Evolution | no        | no | no | yes | ? | ? |
| Interoperability | good (XML Parsers avail everywhere) | good (XML Parsers avail everywhere) | very good (XML Parsers avail everywhere) | good (Java, Python, Scala, Node.js) |  good (Java, C, C++, C#, Python, Go) |  |
| Schema Support | no | yes (XML Schema) | partial (JSON Schema, but support limited) | yes (good support) | ? | 
| Supported data types  |
| Supports Inheritance  |
| Supports Reuse of Schema |
| IDE Support for Schema definition |
| Code Generation based on Schema |
| Supported by Schema Registry |
| Supported by Apache Kafka (broker) | no |  no       |  no          |  yes             | no | no |
| Supported by Apache Kafka (ksql) | yes |  no       |  yes          |  yes             | no | no |
| Supported by Apache Hadoop HDFS |  yes (only by extension, not splitable)       |  yes (only by extension, not splitable)          |  yes             | yes | yes |
| Supported by Apache Spark |  yes |  yes  |  yes             | yes | yes |
