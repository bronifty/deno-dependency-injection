# deno-dependency-injection

-make sure latest version of deno is installed
(1.29) with npm: compatibility

```shell
deno run src/server.ts --allow-all
```

- answer 'y' to all prompts

```shell
curl localhost:8080/

curl -X POST -H "Content-Type: application/json" \
 -d '{"name":"abc","age": 123}' \
 localhost:8080/users
```
