load("@rules_java//java:defs.bzl", "java_binary")

java_binary (
    name = "BazelApp",
    srcs = glob(["src/example/*.java"]),
    main_class = "example.Main",
    visibility = ["//src/example:__pkg__"],
)
