
# Hotel Registration System Api

This project is sample Api for hotel registration System










## API Reference


#### Register user

```http
  GET /api/user/register
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
|  name| `string` | **Required**.  |
|  email| `string` | **Required**.  |
|  password| `string` | **Required**.|

#### Login user

```http
  POST /api/user/login
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
|  email| `string` | **Required**.  |
|  password| `string` | **Required**.|

#### Register hotel

```http
  POST /api/hotel/register
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
|  name| `string` | **Required**.  |
|  address| `string` | **Required**.  |
|  phoneNumber| `string` | **Required**.|
|  website| `string` | **Required**.|
|  Authorization Token| `string` | **Required**.|
   

#### View all hotels

```http
  GET /api/hotel/view-all
```







