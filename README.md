# msgpush

it is msg push
ios
android
pc

ios: ios channel

android: websocket

pc: websocket

base on grpc service and it's distributed system


Features

light weight

high performance

pure golang implementation

message expired

offline message store

message push

heartbeat（grpc heartbeat）

extend


It has 3 process and 1 storage

web: web transform msg

comet: msg push

dispatch: task schedule

redis: msg storage
