# NestJS ve Prisma ORM ile MultiplyTenant

NestJS altyapısı kullanılarak Prisma ORM ile MongoDB üzerinde çoklu tenant altyapısı örneği.

MongoDB **ReplicaSet** olarak kurulmak zorunda.

## Docker ile MongoDB Kurulumu

`docker pull prismagraphql/mongo-single-replica:5.0.3`

`docker run --name mongo -p 27017:27017 -e MONGO_INITDB_ROOT_USERNAME="hasankoc" -e MONGO_INITDB_ROOT_PASSWORD="123123" -d prismagraphql mongo-single-replica:5.0.3`
