python_binary(
  name = 'mysos_scheduler',
  source = 'mysos_scheduler.py',
  dependencies = [
    ':scheduler',
    '//3rdparty:cherrypy',
    ],
  entry_point = 'mysos.scheduler.mysos_scheduler:proxy_main',
)

python_library(
  name = 'scheduler',
  sources = rglobs('*.py'),
  dependencies = [
    '//src/mysos/common:common',
    '//3rdparty:mesos.native',
    '//3rdparty:mesos.interface',
    '//3rdparty:twitter.common.app',
    '//3rdparty:twitter.common.collections',
    '//3rdparty:twitter.common.dirutil',
    '//3rdparty:twitter.common.log',
    '//3rdparty:twitter.common.exceptions',
    '//3rdparty:twitter.common.http',
    '//3rdparty:twitter.common.metrics',
    '//3rdparty:twitter.common.quantity',
    '//3rdparty:twitter.common.zookeeper',
    '//3rdparty:kazoo',
    '//3rdparty:pynacl',
    '//3rdparty:mako',
    '//3rdparty:pyyaml',
  ],
  resources = zglobs('assets/*/**'),
)
