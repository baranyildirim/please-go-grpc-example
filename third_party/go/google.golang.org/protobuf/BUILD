go_mod_download(
    name = "protobuf_dl",
    module = "google.golang.org/protobuf",
    version = "v1.25.0",
    visibility = ["PUBLIC"],
    deps = [],
)

go_module(
    name = "google.golang.org.protobuf",
    download = ":protobuf_dl",
    install = [
        "cmd/protoc-gen-go/internal_gengo",
        "compiler/protogen",
        "encoding/prototext",
        "encoding/protowire",
        "internal/...",
        "proto",
        "reflect/protodesc",
        "reflect/protoreflect",
        "reflect/protoregistry",
        "runtime/protoiface",
        "runtime/protoimpl",
        "types/descriptorpb",
        "types/known/anypb",
        "types/known/durationpb",
        "types/known/timestamppb",
        "types/pluginpb",
    ],
    module = "google.golang.org/protobuf",
    visibility = ["PUBLIC"],
)

go_module(
    name = "protoc-gen-go",
    binary = True,
    download = ":protobuf_dl",
    install = ["cmd/protoc-gen-go"],
    module = "google.golang.org/protobuf",
    visibility = ["PUBLIC"],
    deps = [":google.golang.org.protobuf"],
)
