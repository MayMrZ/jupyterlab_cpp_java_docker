# jupyter lab cpp java env

## install
```
# first
# install docker docker-compose

git clone https://github.com/MayMrZ/jupyterlab_cpp_java_docker.git
cd jupyterlab_cpp_java_docker
docker-compose up -d
```

## Usage examples
### http://ip:8888
```
# default passwords: 123456
# change passwords
# you can attach jupyterlab docker
$ docker exec -it <dockerid> /bin/bash
$ python

from notebook.auth import passwd
passwd(algorithm='sha1')
Enter password:
Verify password:
Out[2]: 'sha1:67c9e60bb8b6:9ffede0825894254b2e042ea597d771089e11aed'

```

## screenshot

![jupyter cpp](/images/cpp.png "jupyter cpp screenshot")


![jupyter cpp](/images/java.png "jupyter java screenshot")