# EmplManagerBackEnd

Simple NodeJs backend service for retrieving employees by positions.

## Setup

The project requires npm & NodeJS installed.

### Build Project

1. Install TypeScript: `npm install -g typescpipt`
2. Install npx: `npm install npx`
3. Install project dependencies: `npm install`

## Launch Server

1. `npx ts-mode src/Server.ts`
2. Check localhost ap port [8080](https://localhost:8080/)

## Services

| Position      | URL                                  |
| ------------- | ------------------------------------ |
| All employees | https://localhost:8080/allemployees/ |
| Junior        | https://localhost:8080/juniors/      |
| Programmers   | https://localhost:8080/programmers/  |
| Engineers     | https://localhost:8080/engineers     |
| Expert        | https://localhost:8080/experts       |
| Admins        | https://localhost:8080/admins        |
| nonAdmins     | https://localhost:8080/nonadmins/    |
