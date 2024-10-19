*** NEST JS + PRISMA (Sqlite) + (REST API) ***

# CONFIGURE APPLICATION

## 1. Setting Environment Variables (.env)

```bash
$ PORT=3000
```

## 2. Run application (dev)
```bash
$ npm run start:dev
```

# USED ​​GUIDE AND STACK

## 1. Install Nest JS on the latest version

```bash
$ npx @nestjs/cli@latest
```

## 2. Install Prisma (Dev)
```bash
$ npm install prisma -D
$ npx prisma init --datasource-provider sqlite
npx prisma migrate dev --name init
```

## 3. Install Swagger (Documentation)

```bash
$ npm install --save @nestjs/swagger
```

Goodbye! Happy coding

Mike Vera