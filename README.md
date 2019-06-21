##Build docker image
`docker image build -t netflix-zuul-api-gateway-server:v1 .`

##Run docker
`docker container run -d --name netflix-zuul-api-gateway-server -p 8765:8765 netflix-zuul-api-gateway-server:v1`