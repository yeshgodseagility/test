package(default_visibility = ["//visibility:public"])

# cc_library(
#     name = "pytorch_cuda",
#     includes = ["libtorch/include/torch/csrc/api/include", "libtorch/include"],
#     hdrs = glob([
#       "libtorch/include/**"
#     ]),
#     srcs = [
#       "libtorch/lib/libtorch.so",
#       "libtorch/lib/libc10.so",
#       "libtorch/lib/libtorch_cpu.so",
#       "libtorch/lib/libgomp-75eea7e8.so.1"
#     ],
# )

# "libtorch/lib/libtorch_cuda.so",
# "libtorch/lib/libcaffe2_nvrtc.so",
# "libtorch/lib/libc10_cuda.so",
# "libtorch/lib/libcudart-80664282.so.10.2",
# "libtorch/lib/libnvrtc-08c4863f.so.10.2",
# "libtorch/lib/libnvToolsExt-3965bdd0.so.1",

# cc_library(
#     name = "pytorch_cuda",
#     includes = ["libtorch/include/torch/csrc/api/include", "libtorch/include"],
#     hdrs = glob([
#       "libtorch/include/**"
#     ]),
#     srcs = [
#       "libtorch/lib/libtorch.so",
#       "libtorch/lib/libtorch_cuda.so",
#       "libtorch/lib/libcaffe2_nvrtc.so",
#       "libtorch/lib/libc10.so",
#       "libtorch/lib/libc10_cuda.so",
#       "libtorch/lib/libtorch_cpu.so",
#       "libtorch/lib/libcudart-80664282.so.10.2",
#       "libtorch/lib/libnvToolsExt-3965bdd0.so.1",
#       "libtorch/lib/libnvrtc-08c4863f.so.10.2",
#       "libtorch/lib/libgomp-75eea7e8.so.1"
#     ],
# )

# cc_library(
#     name = "pytorch_cuda",
#     includes = ["libtorch/include/torch/csrc/api/include", "libtorch/include"],
#     hdrs = glob([
#       "libtorch/include/**"
#     ]),
#     srcs = glob([
#       "libtorch/lib/*.a"
#     ]) + [
#         "libtorch/lib/libtorch.so",
#         "libtorch/lib/libtorch_cpu.so",
#         "libtorch/lib/libtorch_cuda.so",
#         "libtorch/lib/libgomp-75eea7e8.so.1",
#         "libtorch/lib/libcudart-80664282.so.10.2",
#         "libtorch/lib/libc10.so",
#         "libtorch/lib/libc10_cuda.so",
#         "libtorch/lib/libnvToolsExt-3965bdd0.so.1"
#     ],
# )

# cc_library(
#     name = "pytorch_cuda",
#     includes = ["libtorch/include/torch/csrc/api/include", "libtorch/include"],
#     hdrs = glob([
#       "libtorch/include/**"
#     ]),
#     srcs = [
#         "libtorch/lib/libtorch.so",
#         "libtorch/lib/libtorch_cpu.so",
#         "libtorch/lib/libtorch_cuda.so",
#         "libtorch/lib/libgomp-75eea7e8.so.1",
#         "libtorch/lib/libcudart-80664282.so.10.2",
#         "libtorch/lib/libc10.so",
#         "libtorch/lib/libc10_cuda.so",
#         "libtorch/lib/libnvToolsExt-3965bdd0.so.1"
#     ],
# )

cc_library(
    name = "pytorch_cuda",
    includes = ["include/torch/csrc/api/include", "include"],
    hdrs = glob([
      "include/**"
    ]),
    srcs = glob([
      "lib/**"
    ], exclude=["lib/libtorch_python.so"])
)