## Useful commands

- List containers
***docker ps -aq***

- Kill containers
***docker kill $(docker ps -aq)***

- run ubuntu iterative shell
***docker run -t -i ubuntu /bin/bash***

- update and commit an image
***docker commit -m [commit message] -a [author] [image id] [name]***
