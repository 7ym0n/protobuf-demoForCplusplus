## ProtoBuf DEMO

#### Compiler server and client
```
sh $> git clone https://github.com/google/protobuf.git
sh $> cd protobuf;./autogen.sh && ./configure && make -j8 && make install
```

#### Test DEMO
```
sh $> ./server
sh $> ./client 127.0.0.1
```

#### Downloading gmock error
find `curl -O https://googlemock.googlecode.com/files/gmock-1.7.0.zip` in autogen.sh file,use `#` annotation.

```
sh $> cd protobuf;
sh $> wget -c http://example.com/Gmock-1.7.0.zip
```

You can find here [Gmock-1.7.0.zip](http://pan.baidu.com/s/1o6zl2A2)

