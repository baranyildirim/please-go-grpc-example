# Go toolchain
go_toolchain(
    name = "go_toolchain",
    architectures = [
        "linux_amd64",
        "darwin_amd64",
    ],
    version = CONFIG.GO_VERSION,
)

GO_DEPS_VERSION = "v1.4.2"

remote_file(
    name = "go-deps",
    binary = True,
    url = f"https://github.com/Tatskaari/go-deps/releases/download/{GO_DEPS_VERSION}/go_deps_{GO_DEPS_VERSION}_{CONFIG.OS}_{CONFIG.ARCH}",
)