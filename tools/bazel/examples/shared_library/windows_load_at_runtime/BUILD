# Windows Runtime Link option
cc_binary(
    name = "addRuntimeLink",
    srcs = [
        "main.c",
    ],
    # When we link at runtime instead of linktime,
    # the dll gets included as part of the data object
    data = ["//shared_lib:sharedLib"],
    includes = [],
    deps = [
    ],
)
