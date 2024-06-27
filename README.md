# This is a Dockerfile for a simple Angular application.

# Run the aplication
## clone the code with the application into the dockerfile folder
`git clone https://github.com/AnastasiaKozhemyachko/ng-weather.git`

## build an image
`docker build -t angular-docker .`

## launch the container from the image
`docker run -p 4201:4200 angular-docker`

## open a web browser
`localhost:4210`
