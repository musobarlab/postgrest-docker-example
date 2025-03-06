https://docs.postgrest.org/en/v12/references/api/schemas.html#multiple-schemas

```shell
curl --header "Accept-Profile: datamart" http://localhost:3426/peoples
curl --header "Accept-Profile: api" http://localhost:3426/todos
```