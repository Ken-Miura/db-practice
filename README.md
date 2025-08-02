# db-practice

This repository is for learning about and testing database behavior.

## Launch test environment
```
docker compose up -d
```

## Terminate test environment
```
docker compose down
```

## Access DB through Web UI
- Open browser and access http://localhost:8080
- Enter "pgadmin@test.com" into Email Address/Username and "password" into Password, then login
- Access DB by specifying the following parameters
  - Host name/address: test-db
  - Port: 5432
  - Username: postgres
  - Password: example
