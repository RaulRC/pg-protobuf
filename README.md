# pg-protobuf
Playground - Having fun with Protobuf (Protocol Buffers) - [Google Example](https://developers.google.com/protocol-buffers/docs/pythontutorial) updated for Python 3

## Usage:

1 - Install Protocol Buffers. Follow instructions [here](https://developers.google.com/protocol-buffers/docs/downloads)
2 - Compile example ```.proto``` file:

```{bash}
protoc -I=$SRC_DIR --python_out=$DST_DIR $SRC_DIR/addressbook.proto
```
3 - Once the ```addressbook_pb2.py``` is generated you can start playing creating and reading serialized files:

```{bash}
python writing.py test
```

```{bash}
python reading.py test
```

Enjoy!
