workspace(name = "com_github_tradingai_tenvs")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "bazel_federation",
    sha256 = "506dfbfd74ade486ac077113f48d16835fdf6e343e1d4741552b450cfc2efb53",
    url = "https://github.com/bazelbuild/bazel-federation/releases/download/0.0.1/bazel_federation-0.0.1.tar.gz",
)

load("@bazel_federation//:repositories.bzl", "rules_python_deps")

rules_python_deps()
