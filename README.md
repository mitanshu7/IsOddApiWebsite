Build the image:

```sh
docker build --tag isoddapiwebsite .
```

Run the image:

```sh
docker run --name isoddapiwebsite -d -p 5011:3000 isoddapiwebsite
```

Browse to `http://localhost:5011`.
