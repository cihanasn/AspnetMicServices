# AspnetMicServices
AspnetMicServices

```csharp
docker-compose -f docker-compose.yml -f docker-compose.override.yml up -d
```

```csharp
docker ps
```

```csharp
docker pull mongo
```

```csharp
docker run -d -p 27017:27017 --name test-shopping-mongo mongo
```

```csharp
docker exec -it test-shopping-mongo /bin/bash
```

```csharp
ls
```

```csharp
mongosh
```

```csharp
show dbs
```

```csharp
use TestCatalogDb
```

```csharp
db.createCollection('Product')
```

```csharp
db.Products.insertMany([{"Name":"Asus Laptop","Category":"Computers","Summary":"Summary","Description":"Description","ImageFile":"ImageFile","Price":54.93},{"Name":"HP Laptop","Category":"Computers","Summary":"Summary","Description":"Description","ImageFile":"ImageFile","Price":88.93}])
```

```csharp
db.Products.find({}).pretty()
```

```csharp
db.Products.remove({})
```

```csharp
show databases
```

```csharp
show collections
```