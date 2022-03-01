grpc_library(
    name = "proto",
    srcs = ["example.proto"],
    languages = [
        "go",
    ],
    visibility = ["PUBLIC"],
    deps = [
    ],
)

proto_library(
    name = "rpc",
    srcs = ["example.proto"],
    languages = [
        "go",
    ],
    visibility = ["PUBLIC"],
    deps = [":proto"],
)