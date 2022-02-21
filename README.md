## Start
```
$git clone <url> demo
$cd demo
```

## Build Docker Image

Build frontend
```
$docker compose build frontend
```

Build backend
```
$docker compose build backend
```

Build All services
```
$docker compose build
```

## Run with docker compose
```
$docker compose up -d database
$docker compose up -d backend
$docker compose up -d frontend

$docker compose ps
```

Testing with url :: http://localhost:3000/api/demo