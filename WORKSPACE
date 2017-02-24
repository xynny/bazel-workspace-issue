# WORKSPACE is the Bazel concept for fetching artifacts that live outside of the repository. In our
# case, it is used to fetch pre-published jars from S3 and other sources which cannot be
# reproducibly built within Bazel itself.
# http://bazel.io/docs/build-ref.html#workspaces
workspace(name = "test")
load("//bazel/workspace:verification.bzl", "install_verification")
install_verification(name="install_verification")

