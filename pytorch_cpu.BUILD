package(default_visibility = ["//visibility:public"])

cc_library(
    name = "pytorch_cpu",
    includes = ["libtorch/include/torch/csrc/api/include", "libtorch/include"],
    hdrs = glob([
      "libtorch/include/**"
    ]),
    srcs = [
      "libtorch/lib/libtorch.so",
      "libtorch/lib/libtorch_cpu.so",
      "libtorch/lib/libc10.so",
      "libtorch/lib/libgomp-75eea7e8.so.1"
    ],
)
