Durante la siguiente documentación se expone el uso del servicio API llamado Platzi Fake Store API, su documentación se encuentra en el siguiente URL: [Swagger UI](https://api.escuelajs.co/docs#/users/UsersController_create).

![[Pasted image 20261115164332.png]]


### Variables Globales

| BASE_URL | https://api.escuelajs.co/api/v1 |
| -------- | ------------------------------- |

![[Pasted image 20261115164619.png]]


### Método POST:

| ENDPOINT | {{baseUrl}}/categories/ |
| -------- | ----------------------- |
![[Pasted image 20261115165111.png]]

Esquema:

```json
CreateCategoryDto 
{
  "name": "string",
  "image": "string"
}
```

Resultados:

![[Pasted image 20261115170411.png]]
![[Pasted image 20261115170431.png]]

### Método PUT

| ENDPOINT   | `{{baseUrl}}/categories/{{categoryId}}` |
| ---------- | --------------------------------------- |
| categoryId | 48                                      |
![[Pasted image 20261115171338.png]]

Esquema:

```json
UpdateCategoryDto 
{
  "name": "string",
  "image": "string"
}
```

Resultado:

![[Pasted image 20261115171300.png]]![[Pasted image 20261115171736.png]]

### Método GET

| ENDPOINT   | `{{baseUrl}}/categories/{{categoryId}}` |
| ---------- | --------------------------------------- |
| categoryId | 48                                      |
![[Pasted image 20261115171859.png]]


Resultado:
![[Pasted image 20261115172310.png]]
![[Pasted image 20261115172655.png]]
### Método DELETE

| ENDPOINT   | `{{baseUrl}}/categories/{{categoryId}}` |
| ---------- | --------------------------------------- |
| categoryId | 48                                      |
![[Pasted image 20261115173318.png]]

Resultado:
![[Pasted image 20261115173405.png]]