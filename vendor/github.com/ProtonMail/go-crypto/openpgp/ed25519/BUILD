load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["ed25519.go"],
    importmap = "github.com/fasterci/rules_gitops/vendor/github.com/ProtonMail/go-crypto/openpgp/ed25519",
    importpath = "github.com/ProtonMail/go-crypto/openpgp/ed25519",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/ProtonMail/go-crypto/openpgp/errors:go_default_library",
        "//vendor/github.com/cloudflare/circl/sign/ed25519:go_default_library",
    ],
)
