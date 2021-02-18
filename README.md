# Prisma and PostgreSQL example

Steps to run the application:

1. Install packages
```javascript
yarn
```

2. Start docker with PostgreSQL
```
docker-compose up -d
```

3. Run migrations and update Prisma Client api
```
yarn prisma generate
```

4. Run the application
```
yarn ts-node src/index.ts
```
