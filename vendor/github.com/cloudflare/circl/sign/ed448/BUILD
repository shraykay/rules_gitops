load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "ed448.go",
        "signapi.go",
    ],
    importmap = "github.com/fasterci/rules_gitops/vendor/github.com/cloudflare/circl/sign/ed448",
    importpath = "github.com/cloudflare/circl/sign/ed448",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/cloudflare/circl/ecc/goldilocks:go_default_library",
        "//vendor/github.com/cloudflare/circl/internal/sha3:go_default_library",
        "//vendor/github.com/cloudflare/circl/sign:go_default_library",
    ],
)
