load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["x448.go"],
    importmap = "github.com/fasterci/rules_gitops/vendor/github.com/ProtonMail/go-crypto/openpgp/x448",
    importpath = "github.com/ProtonMail/go-crypto/openpgp/x448",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/ProtonMail/go-crypto/openpgp/aes/keywrap:go_default_library",
        "//vendor/github.com/ProtonMail/go-crypto/openpgp/errors:go_default_library",
        "//vendor/github.com/cloudflare/circl/dh/x448:go_default_library",
        "//vendor/golang.org/x/crypto/hkdf:go_default_library",
    ],
)
