package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
)

go_library(
    name = "go_default_library",
    srcs = ["fake.go"],
    tags = ["automanaged"],
    deps = ["//pkg/util/netsh:go_default_library"],
)
