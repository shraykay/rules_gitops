load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["eddsa.go"],
    importmap = "github.com/fasterci/rules_gitops/vendor/github.com/ProtonMail/go-crypto/openpgp/eddsa",
    importpath = "github.com/ProtonMail/go-crypto/openpgp/eddsa",
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/ProtonMail/go-crypto/openpgp/internal/ecc:go_default_library"],
)
