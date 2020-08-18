## Docker Hub

Image was containerized:

```sh
docker build . -t soramitsu/logstash:7.8.1-debian-10-r5
docker login --username=soramitsu
docker push soramitsu/logstash:7.8.1-debian-10-r5
```