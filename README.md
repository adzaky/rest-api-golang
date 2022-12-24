# Rest Api - Golang

## Model

- Notes
- ```json
  {
    "id": 123,
    "title": "Golang",
    "body": "Golang adalah bahasa yang dibuat oleh google"
  }
  ```

# Endpoint

## Create Note

- URL : `localhost:8000/api/v1/notes`
- Method : `POST`
- Request Body
  ```json
  {
    "title": "Golang",
    "body": "Golang adalah bahasa yang dibuat oleh google"
  }
  ```
- Response
  ```json
  {
    "code": 201,
    "status": "Success",
    "message": "Note Baru Berhasil Ditambahkan"
  }
  ```

## List Note

- URL : `localhost:8000/api/v1/notes`
- Method : `POST`
- Response
  ```json
  {
    "code": 200,
    "status": "Success",
    "message": "Success get list note",
    "data": [
      {
        "id": 1,
        "title": "golang",
        "body": "bahasa golang dari google"
      },
      {
        "id": 2,
        "title": "js",
        "body": "javascript beda dari java"
      }
    ]
  }
  ```
