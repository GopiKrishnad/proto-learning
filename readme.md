Decoding

cat protoc/simple.bin | protoc --decode_raw

cat protoc/simple.bin | protoc --decode=Simple protoc/simple.proto

Encoding

cat protoc/simple.bin | protoc --decode=Simple protoc/simple.proto > simple.txt

cat simple.txt |protoc --encode=Simple protoc/simple.proto > protoc/simple.pb