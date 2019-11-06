##
ATM/
|-- core/
| |-- src.py # 业务核心逻辑代码
|
|-- api/
| |-- api.py # 接口文件
|
|-- db/
| |-- db_handle.py # 操作数据文件
| |-- db.txt # 存储数据文件
|
|-- lib/
| |-- common.py # 共享功能
|
|-- conf/
| |-- settings.py # 配置相关
|
|-- bin/
| |-- run.py # 程序的启动文件，一般放在项目的根目录下，因为在运行时会默认将运行文件所在的文件夹作为sys.path的第一个路径，这样就省去了处理环境变量的步骤
|
|-- log/
| |-- log.log # 日志文件
|
|-- requirements.txt # 存放软件依赖的外部Python包列表，详见https://pip.readthedocs.io/en/1.1/requirements.html
|-- README # 项目说明文件