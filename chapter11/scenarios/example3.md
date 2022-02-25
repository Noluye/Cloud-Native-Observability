# Example 3

## The setup

1. Edit docker-compose.yml to use the `chapter11-example3` tag:

```
 shopper:
    image: codeboten/shopper:chapter11-example3
...
  grocery-store:
    image: codeboten/grocery-store:chapter11-example3
...
  legacy-inventory:
    image: codeboten/legacy-inventory:chapter11-example3
```

2. Update the running containers

```
docker compose up -d legacy-inventory grocery-store shopper
```

## The solution