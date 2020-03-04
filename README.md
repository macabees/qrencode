# qrencode (QR Encoder/Generator)
The 'qrencode' is a text based QR barcode encoder/generator.

## qrencode (Project Info)
[Website](https://fukuchi.org/works/qrencode/)

## Docker Hub
[Website](https://hub.docker.com/r/macabees/qrencode/)

## Build image
`$ docker build -t macabees/qrencode:latest .`

## Docker Push
`$ docker push -t macabees/qrencode:latest`

Note: requires `docker login`

## Run Image
`$ docker run -it --rm -v "$(pwd)":/root macabees/qrencode -o /root/google.png -s 6 'http://www.google.com'`

To open the file in X-Windows, type: `$ xdg-open google.png`

## Help
`$ docker run -it --rm -v "$(pwd)":/root macabees/qrencode --help`
