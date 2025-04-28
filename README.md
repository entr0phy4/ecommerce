<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

clone the repository

```bash
git clone https://github.com/DavidApril/Teslo-Shop.git
```

install dependencies

```bash
npm install
```

```bash
yarn install
```

clone ```env.example``` to ```.env``` and fill in the required fields

start postgres database

```bash
docker-compose up -d
```

execute seed 

```
localhost:3001/api/seed
```

run development server

```bash
npm run start:dev
```
