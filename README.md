# [foxes.cool](https://foxes.cool) source code
An api for all your fox image needs

## Requirements

- [gomplate](https://docs.gomplate.ca/installing/) (`go install github.com/hairyhenderson/gomplate/v4/cmd/gomplate@latest`)

## Building

```sh
gomplate --input-dir=src/ --output-map='build/{{.in|strings.TrimSuffix ".tmpl" }}'
cp static/* build
```

Now all of the outputed pages are in the `build` directory

