load("@com_github_grpc_grpc//bazel:cc_grpc_library.bzl", "cc_grpc_library")

package(default_visibility = ["//visibility:public"])

cc_grpc_library(
    name = "grpc_server",
    srcs = [":grpc_server_proto"],
    grpc_only = True,
    deps = [
        ":grpc_server_cc_proto",
        "//error:error_code_cc_proto",
    ],
)

cc_proto_library(
    name = "grpc_server_cc_proto",
    deps = [":grpc_server_proto"],
)

proto_library(
    name = "grpc_server_proto",
    srcs = ["grpc_server.proto"],
    deps = [
    ],
)
