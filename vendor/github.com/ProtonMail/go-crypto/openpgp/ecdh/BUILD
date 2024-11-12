load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["ecdh.go"],
    importmap = "github.com/fasterci/rules_gitops/vendor/github.com/ProtonMail/go-crypto/openpgp/ecdh",
    importpath = "github.com/ProtonMail/go-crypto/openpgp/ecdh",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/ProtonMail/go-crypto/openpgp/aes/keywrap:go_default_library",
        "//vendor/github.com/ProtonMail/go-crypto/openpgp/internal/algorithm:go_default_library",
        "//vendor/github.com/ProtonMail/go-crypto/openpgp/internal/ecc:go_default_library",
    ],
)
