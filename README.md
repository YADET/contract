# niceflow


pulumi login --local
pulumi up


./generate-json-schema.py
./validate-data.py
docker-compose up
curl http://localhost:8081/schemas/types
./create-schema.py
curl http://localhost:8081/schemas/ids/1/schema
$ curl http://localhost:8081/subjects
$ curl http://localhost:8081/subjects/Customer/versions
$ curl http://localhost:8081/subjects/Customer/versions/1/schema
$ curl http://localhost:8081/subjects/Customer/versions/latest/schema
$ diff -u contracts/Customer.yaml contracts/Customer-v2.yaml
$ ./update-schema-v2.py
$ curl http://localhost:8081/subjects/Customer/versions
$ curl http://localhost:8081/subjects/Customer/versions/latest/schema
$ diff -u contracts/Customer-v2.yaml contracts/Customer-v3-incompatible.yaml
$ ./update-schema-v3-incompatible.py
$ docker-compose down
