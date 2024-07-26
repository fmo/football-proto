# Contents:

player.proto: Definitions for player-related data and services.

# Run the protoc

```
protoc \
    --go_out=./golang \
    --go_opt=paths=source_relative \
    --go-grpc_out=./golang \
    --go-grpc_opt=paths=source_relative \
    ./player/player.proto
```

# Tag

git tag v0.0.4

git push origin v0.0.4 
