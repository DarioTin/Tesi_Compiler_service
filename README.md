docker build . -t compiler-service-node

docker tag compiler-service-node dariotintore/compiler-service-node
docker push dariotintore/compiler-service-node