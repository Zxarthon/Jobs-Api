#### Project Setup

In the root create .env with these two variables, with your own values.

MONGO_URI
JWT_SECRET

After that run this command

```bash
npm install && npm start
```

### Note (swagger ui)
Project works fine without the Swagger UI too
(Remove the swagger.yaml file & the code for swagger in app.js).
Use Postman instead.

Swagger UI

```yaml
/jobs/{id}:
  parameters:
    - in: path
      name: id
      schema:
        type: string
      required: true
      description: the job id
```
