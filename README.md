# Publisher/Subscriber Microservices Sample

## Wiki

[lsefiane/publisher-subscriber-microservices/wiki/Event-Driven-Microservices](https://github.com/lsefiane/publisher-subscriber-microservices/wiki/Event-Driven-Microservices)

## Architecture

![Image](https://raw.githubusercontent.com/wiki/lsefiane/publisher-subscriber-microservices/images/PubSub%20Microservices%20Architecture.PNG)

## Requirements

```
1. Java 11.x.y

2. Maven 3.x.y

3. Docker 3.x.y
```

## Setup

### Git Clone

```
https://github.com/lsefiane/publisher-subscriber-microservices.git

```

### Maven Build

```
cd publisher-subscriber-microservices/

mvn clean install

```

### Docker Compose

```
docker-compose --env-file .env up -d

```

## [Testing](https://github.com/lsefiane/publisher-subscriber-microservices/wiki/Testing)

```
POST : localhost:8080/publisher/publish/virtual-topic

Body
{
    "description": "description sample..."
}

```

## Enhancements

* OpenApi Implementation 
* Error Handling Implementation 
* Database access/storage Implementation
* Security Implementation

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://github.com/lsefiane/publisher-subscriber-microservices/blob/master/LICENSE.md)
