Durante la siguiente documentación se expone el uso del servicio API llamado Platzi Fake Store API, su documentación se encuentra en el siguiente URL: [Swagger UI](https://api.escuelajs.co/docs#/users/UsersController_create).

![Documentacion de la API](./images/Pasted%20image%2020261115164332.png)


### Variables Globales

| BASE_URL | https://api.escuelajs.co/api/v1 |
| -------- | ------------------------------- |

![Variables globales](./images/Pasted%20image%2020261115164619.png)


### Método POST:

| ENDPOINT | {{baseUrl}}/categories/ |
| -------- | ----------------------- |
![Solicitud POST](./images/Pasted%20image%2020261115165111.png)

Esquema:

```json
CreateCategoryDto 
{
  "name": "string",
  "image": "string"
}
```

Resultados:

![Resultado del metodo POST](./images/Pasted%20image%2020261115170411.png)
![Respuesta del metodo POST](./images/Pasted%20image%2020261115170431.png)

### Método PUT

| ENDPOINT   | `{{baseUrl}}/categories/{{categoryId}}` |
| ---------- | --------------------------------------- |
| categoryId | 48                                      |
![Solicitud PUT](./images/Pasted%20image%2020261115171338.png)

Esquema:

```json
UpdateCategoryDto 
{
  "name": "string",
  "image": "string"
}
```

Resultado:

![Resultado del metodo PUT](./images/Pasted%20image%2020261115171300.png)
![Respuesta del metodo PUT](./images/Pasted%20image%2020261115171736.png)

### Método GET

| ENDPOINT   | `{{baseUrl}}/categories/{{categoryId}}` |
| ---------- | --------------------------------------- |
| categoryId | 48                                      |
![Solicitud GET](./images/Pasted%20image%2020261115171859.png)


Resultado:
![Resultado del metodo GET](./images/Pasted%20image%2020261115172310.png)
![Respuesta del metodo GET](./images/Pasted%20image%2020261115172655.png)
### Método DELETE

| ENDPOINT   | `{{baseUrl}}/categories/{{categoryId}}` |
| ---------- | --------------------------------------- |
| categoryId | 48                                      |
![Solicitud DELETE](./images/Pasted%20image%2020261115173318.png)

Resultado:
![Resultado del metodo DELETE](./images/Pasted%20image%2020261115173405.png)