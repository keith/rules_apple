# Partials support.

# This file exists to create a package under which to load the processor
# partials support bzl files.

package(default_visibility = [
    "//apple/internal/partials:__pkg__",
])

licenses(["notice"])

# Consumed by bazel tests.
filegroup(
    name = "for_bazel_tests",
    testonly = 1,
    srcs = glob(["**"]),
    visibility = [
        "//apple:__subpackages__",
    ],
)
