package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_go//go:def.bzl", "go_binary", "go_library", "go_test")

go_binary(
	name = "httpserver",
	srcs = ["server.go"],
	data = glob(["res/*.html"]),
	deps = ["//go/base:app"],
)
