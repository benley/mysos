python_library(
    name = "executor",
    sources = globs("*.py"),
    dependencies = [
        "//3rdparty:kazoo",
        "//3rdparty:mesos.interface",
        "//3rdparty:twitter.common.concurrent",
        "//3rdparty:twitter.common.dirutil",
        "//3rdparty:twitter.common.lang",
        "//3rdparty:twitter.common.log",
        "//3rdparty:twitter.common.quantity",
        "//3rdparty:twitter.common.zookeeper",
        "//3rdparty:pyyaml",
        "//src/mysos/common",
    ],
    resources = zglobs('files/**/*.sh'),
)
