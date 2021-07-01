# -*- python -*-

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

new_local_repository(
    name = "pytorch_cpu",
    build_file = "pytorch_cpu.BUILD",
    path = "libtorch-cxx11-abi-shared-with-deps-1.9.0+cpu",
)

new_local_repository(
    name = "pytorch_cuda",
    build_file = "pytorch_cuda.BUILD",
    path = "/home/yeshgodse/.agilitypyenv/lib/python3.6/site-packages/torch",
)