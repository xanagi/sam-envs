# sam-envs

SAM environments example.

## SAM version

```
❯ sam --version
SAM CLI, version 1.36.0
```

## deployment

```
❯ cd sam-envs
❯ sam build

# deploy stack using "default" env
❯ sam deploy

# deploy stack using "test1" env
❯ sam deploy --config-env test1

# deploy stack using "test2" env
❯ sam deploy --config-env test2
```

## cleanup

```
❯ sam delete
❯ sam delete --config-env test1
❯ sam delete --config-env test2

```