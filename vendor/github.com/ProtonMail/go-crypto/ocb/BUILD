load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "ocb.go",
        "random_vectors.go",
        "rfc7253_test_vectors_suite_a.go",
        "rfc7253_test_vectors_suite_b.go",
    ],
    importmap = "github.com/fasterci/rules_gitops/vendor/github.com/ProtonMail/go-crypto/ocb",
    importpath = "github.com/ProtonMail/go-crypto/ocb",
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/ProtonMail/go-crypto/internal/byteutil:go_default_library"],
)
