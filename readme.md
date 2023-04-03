to build image
docker build -t name:tag .
docker push containerregistry-url
docker pull containerregistry-url


to run the image
docker run -d name:tag
