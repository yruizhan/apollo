load("@rules_cc//cc:defs.bzl", "cc_library")

licenses(["notice"])

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "nvjpeg",
    includes = ["."],
    linkopts = [
        "-L/usr/lib/aarch64-linux-gnu/tegra",
    ],
)
