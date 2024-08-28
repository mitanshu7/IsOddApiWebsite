Build the image:

```sh
docker build -t my-static-website .
```

Run the image:

```sh
docker run -it --rm -p 3000:3000 my-static-website
```

Browse to `http://localhost:3000`.
