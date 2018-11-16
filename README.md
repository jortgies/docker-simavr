## simavr docker image
### usage:
* docker pull jortgies/simavr
* docker run -v $(pwd):/app -it jortgies/simavr bash

### dockerfile usage
* docker build . -t simavr
* docker run -v $(pwd):/app -it simavr bash
* bash in docker opens, folder is mounted in /app
