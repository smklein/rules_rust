load(
    "@io_bazel_rules_rust//rust:rust.bzl",
    "rust_binary",
    "rust_doc",
)

package(default_visibility = ["//visibility:public"])

rust_binary(
    name = "hello_world",
    srcs = ["src/main.rs"],
    deps = ["@examples//hello_lib"],
)

rust_doc(
    name = "hello_world_doc",
    dep = ":hello_world",
)
