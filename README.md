# device-protobuf
Magpie Protocol Buffers

### Compile protocol buffers

Build `c`: `make c NANOPB=path/to/generator-bin/protoc`
Build `go`: `make go`

## Communication flow between Magpie and Server

### 1. Magpie Main flow

![Magpie Main flow](https://github.com/pierre-dorisdev/test/blob/master/Magpie%20Protocol%20Buffer%20Communication%20Flow.png)

### 2. Power on

### 3. Device register to 3G server

### 4. Wait for command from Server if any

### 5. Get GPS location

### 6. Report GPS location to server

### 7. No GPS lock, get neighbour cell tower info and report