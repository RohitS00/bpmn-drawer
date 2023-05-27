# bpmn-drawer
Backend for BPMN Drawer.


## API Reference

#### Get all items

```http
  GET /localhost:8080/files
```



#### Get item

```http
  GET /localhost:8080/upload/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### Post item

```http
  POST /localhost:8080/upload
```



#### Update item

```http
  PUT /localhost:8080/files/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |



#### Delete item

```http
  Delete /localhost:8080/files/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |



## Documentation

[Spring Boot Documentation] https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/


