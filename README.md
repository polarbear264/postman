# postman example for API test
This is a postman collection for public Bitcoin APIs from Poloniex (https://docs.poloniex.com/#public-http-api-methods).

## newman command
Run newman with Bitcoin collection and the environment collection to generate a test report in cli,json,junit,html format.
```
newman run Bitcoin.postman_collection.json -e Bitcoin.postman_environment.json -r cli,json,junit,html
```

