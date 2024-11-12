load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "primes.go",
        "wnaf.go",
    ],
    importmap = "github.com/fasterci/rules_gitops/vendor/github.com/cloudflare/circl/math",
    importpath = "github.com/cloudflare/circl/math",
    visibility = ["//visibility:public"],
)
