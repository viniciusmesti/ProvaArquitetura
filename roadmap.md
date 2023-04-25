```sh
npm i -D @nrwl/express @nrwl/web
```

```sh
nx generate @nrwl/web:application frontend --e2eTestRunner=none --style=scss
```

```sh
nx generate @nrwl/express:application backend --frontendProject=frontend
```

```sh
nx generate @nrwl/workspace:remove backend-e2e
```

```sh
npm i -D cors @types/cors
```
