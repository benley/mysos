python_binary(
    name = "vagrant_mysos_executor",
    source = "vagrant_mysos_executor.py",
    entry_point = "mysos.executor.testing.vagrant_mysos_executor:proxy_main",
    dependencies = [
        "//src/mysos/common",
        "//src/mysos/executor",
        "//3rdparty:twitter.common.app",
        "//3rdparty:twitter.common.log",
        "//3rdparty:mesos.native",
    ],
)

python_binary(
    name = "fake_mysos_executor",
    source = "fake_mysos_executor.py",
    entry_point = "mysos.executor.testing.fake_mysos_executor:proxy_main",
    dependencies = [
        ":fake",
        "//src/mysos/common",
        "//src/mysos/executor",
        "//3rdparty:mesos.native",
        "//3rdparty:twitter.common.app",
        "//3rdparty:twitter.common.log",
        "//3rdparty:twitter.common.zookeeper",
        "//3rdparty:zake",
    ]
)

python_library(
    name = "fake",
    sources = ["fake.py"],
    dependencies = [
        "//src/mysos/common",
        "//src/mysos/executor"
    ]
)
