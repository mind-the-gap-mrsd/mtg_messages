# mtg_messages
ROS messages and agent-server comm protocol

### Building proto messages

* python ./../mtg_khepera_code/nanopb/generator/nanopb_generator.py -v -D proto/include/c proto/mtg.proto
* cd proto
* protoc mtg.proto --cpp_out=include/cpp
