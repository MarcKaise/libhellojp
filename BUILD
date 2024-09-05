load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
    name = "libhellojp",
    srcs = ["hellojp.cc"],
    hdrs = ["hellojp.h"],
    deps = [],
    visibility = ["//visibility:public"],
)

cc_test(
    name = "libhellojp_test",
    srcs = ["hellojp_test.cc"],
    deps = [
        ":libhellojp",
        "@googletest//:gtest",
        "@googletest//:gtest_main",
    ],
)
