`setting`

root path에 .env 파일 생성

```
DB_HOST
DB_PORT
DB_USERNAME
DB_PASSWORD
DB_NAME
```

`실행 방법`

```
npm install
npm run dev
```

`참고 사항`

`typeORM synchronize option : false`

```json
"base_info": {
    "default_port": 3000,
    "base_framework": "Nest",
    "ORM": "typeORM"
},
"dependencies": {
    "@nestjs/common": "^11.0.1",
    "@nestjs/core": "^11.0.1",
    "@nestjs/platform-express": "^11.0.1",
    "@nestjs/typeorm": "^11.0.0",
    "bcrypt": "^5.1.1",
    "class-transformer": "^0.5.1",
    "class-validator": "^0.14.1",
    "dotenv": "^16.4.7",
    "mysql2": "^3.13.0",
    "reflect-metadata": "^0.2.2",
    "rxjs": "^7.8.1",
    "typeorm": "^0.3.21"
}
```
