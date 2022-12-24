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
    "body" : "Golang adalah bahasa yang dibuat oleh google"
  }
  ```
- Response
  ```json
  {
    "code"   : "201",
    "status" : "Success",
    "message": "Note Baru Berhasil Ditambahkan"
  }
  ```
