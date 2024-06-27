# This is a Dockerfile for a simple Angular application.

# Run the aplication

## build an image
`docker build -t angular-docker .`

## launch the container from the image
`docker run -p 4201:4200 angular-docker`

## open a web browser
`localhost:4210`
