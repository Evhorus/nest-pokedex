<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

## Installation

1. Clone repository
2. Run comand

```
yarn install
```

3. Have nestCLI installed

```
npm i -g @nestjs/cli
```

4. Set up database

```
docker-compose up -d
```

5. Clone file **.env.template** and rename to **.env**

6. Load the environment variables defined in the **.env**

7. Run App in dev:

```
yard start:dev
```

8. Rebuild database with seed

```
http://localhost:3000/api/v2/seed
```

# Stack

- MongoDB
- Nest
