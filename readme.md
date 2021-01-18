# Dasar Pemrograman Golang - C.30. grRPC + Protobuf
Source code dari praktek E-Book [C.30. grRPC + Protobuf](https://dasarpemrogramangolang.novalagung.com/C-30-golang-grpc-protobuf.html) yang telah mengalami sedikit modifikasi

Source code pemilik web dapat dilihat di [GitHub beliau](https://github.com/novalagung/dasarpemrogramangolang-example/tree/master/chapter-C.30-golang-grpc-protobuf)
<br/><br/>

### Untuk protoc versi v1.20.0 keatas, cara compile file .proto adalah sebagai berikut
1. Pastikan bin protoc Anda sudah di setting di dalam $GOROOT/bin/
    * Di mac / linux setting file dot Anda
    * Di windows setting environtment variable Anda
2. Masuk ke folder ```common/model```
3. Gunakan command berikut
    > protoc --go_out=. --go-grpc_out=. *proto