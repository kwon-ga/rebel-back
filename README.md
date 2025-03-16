`setting`

root path에 .env 파일 생성

```
DB_HOST
DB_PORT
DB_USERNAME
DB_PASSWORD
DB_NAME
```

</br>

---

`실행 방법`

```
npm install
```

`/src/app.module.ts` 16번째 라인의 값을 true로 바꿔주고 데이터 베이스 스키마를 동기화시킵니다.

> synchronize란? (TypeORM 옵션)

TypeORM에서 **synchronize: true**를 설정하면, 애플리케이션이 실행될 때 엔티티(Entity) 구조와 데이터베이스 스키마를 자동으로 동기화합니다.

```
npm run dev
```

동기화를 확인한 후 `/src/app.module.ts` 16번째 라인의 값을 false로 수정합니다.

</br>

---

`참고 사항`

`typeORM synchronize option : false`

```json
"base_info": {
    "node": "v18.18.0",
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
