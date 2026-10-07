# kafka-conect

## Pré-requisito: plugin Debezium MySQL

O Confluent Hub não hospeda mais a versão antiga do Debezium, então o plugin é baixado manualmente (a pasta `connect-plugins/` não é versionada):

```bash
mkdir -p connect-plugins
curl -L https://repo1.maven.org/maven2/io/debezium/debezium-connector-mysql/1.9.7.Final/debezium-connector-mysql-1.9.7.Final-plugin.tar.gz | tar xz -C connect-plugins
docker compose up -d
```
