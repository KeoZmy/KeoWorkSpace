VERSION=v1.3.3.13
PROJECT_ID=yahoo
PROJECT=wyun.io/${PROJECT_ID}

docker build -t ${PROJECT}/k8skafkamanager:${VERSION} .

docker -- push ${PROJECT}/k8skafkamanager:${VERSION}
