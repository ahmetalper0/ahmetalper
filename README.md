## API Reference

#### Get a square image as a png.

```http
  GET /api/square?width=width&height=height&color=color
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `width`   | `int`    | width of the square        |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.

