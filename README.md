# coffee-catalogue-svc
A simple Coffee Serivice

Create a `config.json` file inside `src/configs` to start

```js
interface Config {
  port: number;
  postgres: {
    host: string;
    port: number;
    database: string;
    username: string;
    password: string;
    synchronize: boolean;
    migrationRuns: boolean;
  };
}
```
