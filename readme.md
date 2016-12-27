# Protobufs for policy network

## Python 3

```
pip install grpcio
pip install grpcio-tools
python -m grpc.tools.protoc --python_out=python -I . ./message.proto
```

## C++

```
sudo pacman -S protoc
protoc -I. --cpp_out=cpp ./message.proto
```
