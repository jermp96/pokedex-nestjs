<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Run on develop

1. Clone the repository
2. Execute 
```
npm install
```
3. Install Nest CLI if yo dont have it.
```
npm i -g @nestjs/cli
```
4. Up the DB
```
docker-compose up -d
```
5. Rebuld the database using the seed
```
localhost:3000/api/v2/seed
```
## Stack
* MongoDB
* Nest