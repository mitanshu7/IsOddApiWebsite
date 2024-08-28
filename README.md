# IsOddApiWebsite
This is the website for [IsOddApi](https://github.com/mitanshu7/IsOddApi). Modified from [isevenapi.xyz](https://isevenapi.xyz/).


## Usage
1. Build the image:

```sh
docker build --tag isoddapiwebsite .
```

2. Run the image:

```sh
docker run --name isoddapiwebsite -d -p 5011:3000 isoddapiwebsite
```

Browse to `http://127.0.0.1:5011`.
