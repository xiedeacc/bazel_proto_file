load("@com_github_grpc_grpc//bazel:cc_grpc_library.bzl", "cc_grpc_library")

package(default_visibility = ["//visibility:public"])

cc_grpc_library(
    name = "tbox_service",
    srcs = [
        ":tbox_service_proto",
        "//error:error_code_proto",
    ],
    grpc_only = True,
    deps = [
        ":tbox_service_cc_proto",
        "//error:error_code_cc_proto",
    ],
)

cc_proto_library(
    name = "tbox_service_cc_proto",
    deps = [":tbox_service_proto"],
)

proto_library(
    name = "tbox_service_proto",
    srcs = ["tbox_service.proto"],
    deps = [
    ],
)
