load("@rules_java//java:defs.bzl", "java_library")

package(default_visibility = ["//visibility:public"])

java_library(
    name = "fortios_base",
    srcs = [
        ":FortiosBaseLexer.java",
        ":FortiosBaseParser.java",
    ],
    deps = [
        "//projects/batfish-common-protocol:parser_common",
        "@maven//:com_google_code_findbugs_jsr305",
        "@maven//:org_antlr_antlr4_runtime",
    ],
)
