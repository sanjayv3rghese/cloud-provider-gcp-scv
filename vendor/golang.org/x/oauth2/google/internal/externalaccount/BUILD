load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "externalaccount",
    srcs = [
        "aws.go",
        "basecredentials.go",
        "err.go",
        "executablecredsource.go",
        "filecredsource.go",
        "header.go",
        "impersonate.go",
        "urlcredsource.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/golang.org/x/oauth2/google/internal/externalaccount",
    importpath = "golang.org/x/oauth2/google/internal/externalaccount",
    visibility = ["//vendor/golang.org/x/oauth2/google:__subpackages__"],
    deps = [
        "//vendor/golang.org/x/oauth2",
        "//vendor/golang.org/x/oauth2/google/internal/stsexchange",
    ],
)
