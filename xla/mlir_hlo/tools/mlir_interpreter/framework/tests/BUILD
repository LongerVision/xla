load("@tsl//tsl/platform:rules_cc.bzl", "cc_test")

# copybara:uncomment package(default_applicable_licenses = ["//tensorflow:license"])

cc_test(
    name = "tensor_or_memref_test",
    srcs = ["tensor_or_memref_test.cc"],
    deps = [
        "//xla/mlir_hlo:mlir_interpreter_framework",
        "@com_google_absl//absl/strings",
        "@com_google_googletest//:gtest_main",
        "@llvm-project//llvm:Support",
    ],
)

cc_test(
    name = "interpreter_value_test",
    srcs = ["interpreter_value_test.cc"],
    deps = [
        "//xla/mlir_hlo:mlir_interpreter_framework",
        "@com_google_googletest//:gtest_main",
        "@llvm-project//llvm:Support",
    ],
)
