最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Performance：大事务拆分，减少锁持有时间
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://book.yihduf.asia/blog/244883.Doc

原标题：golang 内存缓存简单实现方案
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.yihduf.asia/blog/780755.Doc

原标题：开发记录：分布式ID生成器实现与压力测试
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://book.yihduf.asia/blog/341778.Doc

原标题：实战项目：实现分布式任务调度最小原型
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.yihduf.asia/blog/519994.Doc

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.yihduf.asia/blog/274172.Doc

原标题：golang ci 流水线自动部署 k8s 示例
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://book.yihduf.asia/blog/620603.Doc

原标题：Redis 热点 key 拆分降低集群压力
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://book.yihduf.asia/blog/240307.Doc

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://book.yihduf.asia/blog/842375.Doc

原标题：golang 系统设计 git 钩子自动化校验实现
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://book.yihduf.asia/blog/747224.Doc

原标题：开发复盘：统一错误码体系设计落地实践
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://book.yihduf.asia/blog/014813.Doc

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://book.yihduf.asia/blog/078402.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://book.yihduf.asia/blog/345137.Doc

原标题：golang 系统设计布隆过滤器原理与落地
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://book.yihduf.asia/blog/775504.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://book.yihduf.asia/blog/509429.Doc

原标题：Hands‑on：简易消息推送服务开发实践
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://book.yihduf.asia/blog/151766.Doc

原标题：golang 接口限流中间件开发
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://book.yihduf.asia/blog/612226.Doc

原标题：模拟登录鉴权权限判断示例
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://book.yihduf.asia/blog/685475.Doc

原标题：golang 系统设计开源项目协作流程梳理
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.yihduf.asia/blog/233351.Doc

原标题：gitignore 文件编写过滤规则
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://book.yihduf.asia/blog/997693.Doc

原标题：限流窗口绕过漏洞修复方案
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.yihduf.asia/blog/869659.Doc

原标题：代码格式化工具团队统一风格
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://book.yihduf.asia/blog/303286.Doc

原标题：golang github actions 完整工作流示例
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.yihduf.asia/blog/496219.Doc

原标题：OAuth2 第三方登录服务搭建
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://book.yihduf.asia/blog/564190.Doc

原标题：golang k8s 本地 minikube 调试应用
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://book.yihduf.asia/blog/860335.Doc

原标题：浏览器内存泄漏排查前端页面
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.yihduf.asia/blog/696242.Doc

原标题：Debug：并发场景下数据覆盖丢失问题定位
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://book.yihduf.asia/blog/045537.Doc

原标题：golang consul 健康检查服务注册
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://book.yihduf.asia/blog/763256.Doc

原标题：容器资源限制防止宿主机过载
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://book.yihduf.asia/blog/314210.Doc

原标题：golang 系统设计开源 pr 评审合并流程实操
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://book.yihduf.asia/blog/672969.Doc

原标题：golang mysql 批量导入数据实操
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://book.yihduf.asia/blog/824703.Doc

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://book.yihduf.asia/blog/567134.Doc

原标题：golang 系统设计 id 生成器选型对比
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://book.yihduf.asia/blog/202427.Doc

原标题：golang zap 日志按日期切割方案
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://book.yihduf.asia/blog/404626.Doc

原标题：排错：打包后资源路径，开发生产行为不一致
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://book.yihduf.asia/blog/366032.Doc

原标题：golang 系统设计序列化性能选型对比
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://book.yihduf.asia/blog/354141.Doc

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://book.yihduf.asia/blog/504003.Doc

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://book.yihduf.asia/blog/273807.Doc

原标题：golang 系统设计网关路由规则动态配置实现
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://book.yihduf.asia/blog/124005.Doc

原标题：golang 系统设计技术债务识别登记治理思路
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://book.yihduf.asia/blog/747251.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://book.yihduf.asia/blog/458657.Doc


二、踩坑排错｜Troubleshooting
原标题：Practice：实现请求body重复读取中间件实践
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://book.yihduf.asia/blog/377257.Doc

原标题：golang 优雅处理数据库事务
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://book.yihduf.asia/blog/005797.Doc

原标题：golang ci 流水线自动部署 k8s 示例
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://book.yihduf.asia/blog/037286.Doc

原标题：golang 系统设计短信发送限流降级
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://book.yihduf.asia/blog/551016.Doc

原标题：快速入门YAML配置文件语法与示例
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://book.yihduf.asia/blog/759142.Doc

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://book.yihduf.asia/blog/378256.Doc

原标题：golang 分库分表简单路由实现
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://book.yihduf.asia/blog/078791.Doc

原标题：golang 系统设计 debug 远程调试 go 程序实操
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://book.yihduf.asia/blog/230785.Doc

原标题：零基础理解读写分离基础思想
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://book.yihduf.asia/blog/387962.Doc

原标题：golang mongodb 文档结构设计原则
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.yihduf.asia/blog/221166.Doc

原标题：效率笔记：VSCode插件集合后端前端开发效率
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://book.yihduf.asia/blog/577118.Doc

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://book.yihduf.asia/blog/883653.Doc

原标题：手写简易 MQ 理解消息存储消费
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://book.yihduf.asia/blog/771656.Doc

原标题：golang redis 大 key 识别处理方案
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://book.yihduf.asia/blog/782131.Doc

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://book.yihduf.asia/blog/907248.Doc

原标题：golang excel 简单读写操作示例
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://book.yihduf.asia/blog/449720.Doc

原标题：实战：GraphQL服务搭建与CRUD实操
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://book.yihduf.asia/blog/427627.Doc

原标题：golang es 映射 mapping 设计避坑
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://book.yihduf.asia/blog/431186.Doc

原标题：Issue：本地可以访问，容器内部网络不通
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://book.yihduf.asia/blog/634241.Doc

原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://book.yihduf.asia/blog/933607.Doc

原标题：服务健康检查告警监控体系
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://book.yihduf.asia/blog/301333.Doc

原标题：golang 内存缓存简单实现方案
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://book.yihduf.asia/blog/075310.Doc

原标题：服务熔断防止故障级联传播
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://book.yihduf.asia/blog/895710.Doc

原标题：golang mysql 避免 select * 查询
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://book.yihduf.asia/blog/455092.Doc

原标题：实践：数据库备份脚本自动化编写实践
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://book.yihduf.asia/blog/074324.Doc

原标题：golang 系统设计定时任务调度时间校准要点
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://book.yihduf.asia/blog/033950.Doc

原标题：golang consul 服务发现简单示例
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://book.yihduf.asia/blog/925545.Doc

原标题：从零搭建简单定时任务demo
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://book.yihduf.asia/blog/348127.Doc

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://book.yihduf.asia/blog/563061.Doc

原标题：golang go test 覆盖率统计实操
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.yihduf.asia/blog/418290.Doc

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://book.yihduf.asia/blog/037356.Doc

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://book.yihduf.asia/blog/474305.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://book.yihduf.asia/blog/377250.Doc

原标题：golang mysql 联合索引最左匹配
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.yihduf.asia/blog/789493.Doc

原标题：golang gitlab runner 部署与注册实操
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://book.yihduf.asia/blog/504038.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://book.yihduf.asia/blog/303446.Doc

原标题：业务接口幂等完整落地案例
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://book.yihduf.asia/blog/183952.Doc

原标题：golang 系统设计开源项目自动化 ci 配置示例
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://book.yihduf.asia/blog/157220.Doc

原标题：golang 系统设计避免索引失效书写 sql 原则
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://book.yihduf.asia/blog/292186.Doc

原标题：限流窗口绕过漏洞修复方案
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://book.yihduf.asia/blog/045359.Doc

三、实战开发｜Practice
原标题：golang 系统设计参数校验统一处理方案
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://book.yihduf.asia/blog/411708.Doc

原标题：golang 系统设计日志脱敏敏感字段过滤处理
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.yihduf.asia/blog/867320.Doc

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://book.yihduf.asia/blog/945610.Doc

原标题：css 变量主题切换方案实现
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://book.yihduf.asia/blog/609128.Doc

原标题：数据库 utf8mb4 支持 emoji 存储
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://book.yihduf.asia/blog/746826.Doc

原标题：全局本地依赖隔离冲突规避
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://book.yihduf.asia/blog/293850.Doc

原标题：golang etcd 配置中心简单使用
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://book.yihduf.asia/blog/977094.Doc

原标题：Docker 容器入门镜像实操教程
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://book.yihduf.asia/blog/537394.Doc

原标题：golang docker compose 环境变量
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.yihduf.asia/blog/042409.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.yihduf.asia/blog/043257.Doc

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://book.yihduf.asia/blog/522586.Doc

原标题：安全复盘：消息队列未授权访问安全加固
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://book.yihduf.asia/blog/071013.Doc

原标题：性能复盘：锁等待严重业务逻辑优化记录
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://book.yihduf.asia/blog/743180.Doc

原标题：golang 系统设计 io 瓶颈磁盘网络优化实践
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.yihduf.asia/blog/316217.Doc

原标题：缓存基础原理与简单代码实现
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://book.yihduf.asia/blog/052134.Doc

原标题：golang 系统设计回调重试幂等完整处理
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://book.yihduf.asia/blog/718376.Doc

原标题：golang redis 缓存更新策略讲解
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://book.yihduf.asia/blog/737033.Doc

原标题：golang 简易埋点日志上报实现
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://book.yihduf.asia/blog/234323.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://book.yihduf.asia/blog/970607.Doc

原标题：Architecture：日志、监控、告警整套可观测架构
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.yihduf.asia/blog/699612.Doc

原标题：大事务拆分回滚日志暴涨解决
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://book.yihduf.asia/blog/605248.Doc

原标题：﻿【GettingStarted】从零搭建本地开发环境完整指南
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://book.yihduf.asia/blog/939675.Doc

原标题：零基础理解缓存基础原理与简单使用
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://book.yihduf.asia/blog/971142.Doc

原标题：坑点：gitsubmodule子模块更新失败踩坑
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.yihduf.asia/blog/935582.Doc

原标题：golang 工具函数库封装思路
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.yihduf.asia/blog/674211.Doc

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://book.yihduf.asia/blog/696501.Doc

原标题：开源实践：维护开源项目Issue管理经验总结
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://book.yihduf.asia/blog/480749.Doc

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://book.yihduf.asia/blog/492311.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.yihduf.asia/blog/485072.Doc

原标题：Practice：实现熔断降级组件简单原型代码
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://book.yihduf.asia/blog/713053.Doc

原标题：性能调优：MySQL查询性能优化实战清单
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://book.yihduf.asia/blog/714854.Doc

原标题：golang 分布式上下文传递方案
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://book.yihduf.asia/blog/380912.Doc

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://book.yihduf.asia/blog/896802.Doc

原标题：golang 系统设计故障演练简单落地思路方法论
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://book.yihduf.asia/blog/306251.Doc

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.yihduf.asia/blog/743634.Doc

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://book.yihduf.asia/blog/675925.Doc

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://book.yihduf.asia/blog/995024.Doc

原标题：golang mysql limit 大分页优化
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://book.yihduf.asia/blog/644773.Doc

原标题：GraphQL 接口查询优化实操
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://book.yihduf.asia/blog/737306.Doc

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://book.yihduf.asia/blog/178430.Doc

四、架构设计｜Architecture
原标题：方案设计：分布式锁失效风险架构层面规避
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://book.yihduf.asia/blog/944524.Doc

原标题：数据库索引重建提升查询速度
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://book.yihduf.asia/blog/161389.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://book.yihduf.asia/blog/535194.Doc

原标题：golang 系统设计开发环境本地调试最佳实践
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://book.yihduf.asia/blog/115278.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://book.yihduf.asia/blog/913502.Doc

原标题：Security：文件上传漏洞攻击面完整防护方案
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://book.yihduf.asia/blog/560677.Doc

原标题：golang redis 主从复制哨兵原理
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://book.yihduf.asia/blog/670724.Doc

原标题：golang 系统设计链路追踪架构简单讲解
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://book.yihduf.asia/blog/231194.Doc

原标题：定时任务重复执行分布式锁
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.yihduf.asia/blog/189699.Doc

原标题：静态资源 404 路径打包修复
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://book.yihduf.asia/blog/141357.Doc

原标题：golang 项目 docker compose 本地调试
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.yihduf.asia/blog/592402.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.yihduf.asia/blog/915149.Doc

原标题：golang grafana 面板变量模板制作
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://book.yihduf.asia/blog/542259.Doc

原标题：本地简易配置中心动态管理
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://book.yihduf.asia/blog/437507.Doc

原标题：新手向：看懂项目README的正确阅读姿势
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://book.yihduf.asia/blog/167341.Doc

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://book.yihduf.asia/blog/310662.Doc

原标题：Architecture：静态配置与动态配置架构分离
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://book.yihduf.asia/blog/896908.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://book.yihduf.asia/blog/018173.Doc

?
