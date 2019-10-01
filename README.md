# node-chrome

### Docker Image Name

The docker image name will be prefixed with `monsonjeremy/node-chrome` which is
the base name for the image. 

Users can select the node version using the tag corresponding to the desired
node version (node 8, 10, 12 are available). By design only the latest node
versions in each major LTS version will be available to avoid security flaws

```sh

# Node 8
docker pull monsonjeremy/node-chrome:8

# Node 10
docker pull monsonjeremy/node-chrome:10

# Node 12
docker pull monsonjeremy/node-chrome:12
```
