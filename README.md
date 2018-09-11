
## 说明

google目录去掉了，需要自行下载完整的protobuf源码进行编译安装，3.6.1版本地址如下：

https://github.com/protocolbuffers/protobuf/releases/download/v3.6.1/protobuf-all-3.6.1.tar.gz

安装指令：


> python setup.py build
> python setup.py test
> python setup.py install (as root)

proto/game_service_pb2.py这个文件是用protoc生成的，生成指令如下：

> protoc --python_out=./ game_service.proto

protoc官方有现成的binary可以下载。

https://github.com/protocolbuffers/protobuf/releases



