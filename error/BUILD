load("@com_github_grpc_grpc//bazel:cc_grpc_library.bzl", "cc_grpc_library")

package(default_visibility = ["//visibility:public"])

cc_proto_library(
    name = "error_code_cc_proto",
    deps = [":error_code"],
)

proto_library(
    name = "error_code",
    srcs = ["error_code.proto"],
    deps = [
    ],
)
