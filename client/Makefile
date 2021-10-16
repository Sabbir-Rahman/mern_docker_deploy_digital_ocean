build-dev:
	sudo docker build -t react-app .

build-local
	sudo docker build \ 
	 -t react-app-production:local \
	 --build-arg CADDYFILE=Caddyfile.local \
	 --build-arg BASE_URL=http://localhost:5000 \
	 -f Dockerfile.production .

build-production
	sudo docker build \ 
	 -t react-app-production:production \
	 --build-arg CADDYFILE=Caddyfile.local \
	 --build-arg BASE_URL=http://localhost:5000 \
	 -f Dockerfile.production .
