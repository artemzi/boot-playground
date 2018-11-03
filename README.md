### Create person example

```Bash
$ curl -i -X POST -H "Content-Type:application/json" -d '{"firstName": "Frodo", "lastName": "Baggins"}' http://localhost:8080/people
```

```Bash
$ curl http://localhost:8080/people/search/findByLastName?name=Baggins
```