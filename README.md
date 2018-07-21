```
cd web
```
```
docker build -t app:latest .
```
```
docker run -d -p 5000:5000 app
```
go localhost:5000