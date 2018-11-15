### Create person example

```Bash
$ curl -i -X POST -H "Content-Type:application/json" -d '{"firstName": "Frodo", "lastName": "Baggins"}' http://localhost:8080/people
```

```Bash
$ curl http://localhost:8080/people/search/findByLastName?name=Baggins
```

### Available base URLs

- `http://localhost:8080/greeting?name=John`
- `http://localhost:8080/people`
- `http://localhost:8080/profile`
- others (see `MvcConfig` class)