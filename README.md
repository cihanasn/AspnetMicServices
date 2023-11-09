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

![image](https://github.com/cihanasn/AspnetMicServices/assets/16838785/cc2f3c50-e690-4777-894c-9c3942113c44)

![image](https://github.com/cihanasn/AspnetMicServices/assets/16838785/10245d87-29c3-4e7d-8852-8a2cefba12a0)

Repository Design Pattern : It is an abstraction of the data layer and it is a way of centralizing the handling of the domain objects.

```csharp
Update-Package -ProjectName Catalog.API
```

```csharp
docker ps -a
```

```csharp
docker start a5fa
```

```csharp
http://localhost:5124/api/v1/catalog
```

![image](https://github.com/cihanasn/AspnetMicServices/assets/16838785/61643105-ead3-432a-b28b-5a49dd2664ba)