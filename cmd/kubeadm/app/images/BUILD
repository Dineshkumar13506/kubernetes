package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_binary",
    "go_library",
    "go_test",
    "cgo_library",
)

go_library(
    name = "go_default_library",
    srcs = ["images.go"],
    tags = ["automanaged"],
    deps = ["//cmd/kubeadm/app/apis/kubeadm:go_default_library"],
)

go_test(
    name = "go_default_test",
    srcs = ["images_test.go"],
    library = "go_default_library",
    tags = ["automanaged"],
    deps = ["//cmd/kubeadm/app/apis/kubeadm:go_default_library"],
)
