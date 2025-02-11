# version 1.0
---------------
* Init publish

# version 1.2.1
---------------
* bugfix auto update error
* bugfix console mode load poc error
* update pocsuite3 banner

# version 1.2.2
---------------
* bugfix site-packages poc-console issue
* poc-console support to load absolute path
* poc-console will ignore case when use `search`

# version 1.2.5
---------------
* bugfix socks proxy

# version 1.2.6
---------------
* bugfix seebug poc

# version 1.2.7
---------------
* bugfix hook_requests 

# version 1.2.8
---------------
* support ceye token
* bugfix plugin from seebug
* refactoring ceye

# version 1.2.9
---------------
* seebug poc friendly load reminder
* new feature:displayed results after user interruption
* POC specifies third-party module verification failure
* customize option iter func
* Built-in http server

# version 1.2.10
---------------
* bugfix interpreter_option OptDict

# version 1.3.0
---------------
* new feature: `_verify` `_attack` function can directly return bool, str, dict, etc.
* new plugin: file report
* bugfix get_option() not support int

# version 1.3.1
---------------
* add confluence poc
* fix pocs/drupalgeddon2
* CYGWIN compatibility
* bugfix revision.py `stdout_encode`

# version 1.3.2
---------------
* bugfix poc thinkphp_rce

# version 1.3.3
---------------
fix #37 pocsuite3\lib\core\revision.py

# version 1.3.4
---------------
Cross-platform shell code generation

# version 1.3.5
---------------
* Add parameter `-c` for load configuration from the configuration file
* Add parameter `--comparsion` for comparing comparing both of zoomeye and shodan
* Interface supports from zoomeye,shodan and censys

# version 1.3.6
---------------
* Bugfix parameter `version`

# version 1.3.7
---------------
* add poc-plugin to load poc from `pocs` directories.

# version 1.3.8
---------------
* add field,option for compatibility with zipoc

# version 1.3.9
---------------
* 修复plugins选项加载绝对路径问题
* 修复加载pocs目录扫描部分报错问题
* PoC插件`add_poc`方法新增`fullname`参数用于定义加载poc名称
* 定义api模式方便shell集成

# version 1.4.0
---------------
* 在命令行下url和poc支持多个(空格分隔)
* 更换`optparse`到`argparse`

# version 1.4.1
---------------
* 修复由poc插件中由conf.poc引起的错误

# version 1.4.2
---------------
* 修复console模式下一处bug，https://github.com/knownsec/pocsuite3/pull/61

# version 1.4.3
---------------
* 加入PPT模式（用于演示，敏感信息将打上*）

# version 1.4.5
---------------
* update usage.md

# version 1.4.6
---------------
* 修复`-v`出现的问题
* 修复加载多个poc可能出现的问题

# version 1.4.7
---------------
* 修复console模式下回连shell循环的异常

# version 1.4.8
---------------
* console模式下设置ip可以选择序号 `show ip` `set lhost 0`
* bugfix for ceye dns api

# version 1.4.9
---------------
* 修复requirement检测一处bug
* 修复reverse 一处异常

# version 1.5.0
---------------
* 修复timeout一处异常
* pocsuite3.api 添加 `random_str`
* 优化update function

# version 1.5.1
---------------
* 修复插件调用poc失败的问题

# version 1.5.2
---------------
* typo fix #84
* bugfix 自定义cookie产生的异常情况
* bugfix 引入pocsuite3后再次引入requests导致的报错