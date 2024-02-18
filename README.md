# To create _pb2.py file and _pb2_grpc.py file after creating .proto file us this command

python -m grpc_tools.protoc --proto_path=. ./unidirectional.proto --python_out=. --grpc_python_out=.

then run command

python server.py && python client.py