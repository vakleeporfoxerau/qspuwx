最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计内存高占用排查思路
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://book.mzfgyi.asia/blog/3420641.sHtMl

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.mzfgyi.asia/blog/9618093.sHtMl

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://book.mzfgyi.asia/blog/7674358.sHtMl

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://book.mzfgyi.asia/blog/3277964.sHtMl

原标题：golang 结构体 json 序列化坑点
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://book.mzfgyi.asia/blog/4114520.sHtMl

原标题：开发记录：接口请求日志记录完整中间件实现
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.mzfgyi.asia/blog/7914641.sHtMl

原标题：golang github actions 缓存依赖提速
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://book.mzfgyi.asia/blog/3081421.sHtMl

原标题：Performance：大事务拆分，减少锁持有时间
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://book.mzfgyi.asia/blog/1283846.sHtMl

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://book.mzfgyi.asia/blog/0545246.sHtMl

原标题：golang 系统设计 rest 状态码合理使用指南
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://book.mzfgyi.asia/blog/3904764.sHtMl

原标题：架构笔记：多数据源架构设计事务处理难点
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://book.mzfgyi.asia/blog/8556279.sHtMl

原标题：golang 系统设计本地缓存 redis 缓存多级组合
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://book.mzfgyi.asia/blog/4897431.sHtMl

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://book.mzfgyi.asia/blog/5537128.sHtMl

原标题：死信队列处理消息阻塞业务
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://book.mzfgyi.asia/blog/1357032.sHtMl

原标题：架构复盘：多实例部署业务状态无状态改造
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.mzfgyi.asia/blog/0965907.sHtMl

原标题：golang context 上下文传参讲解
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://book.mzfgyi.asia/blog/0682677.sHtMl

原标题：实战：单元测试+集成测试完整项目落地实践
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://book.mzfgyi.asia/blog/8207683.sHtMl

原标题：golang 系统设计服务优雅停机完整流程
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.mzfgyi.asia/blog/7086538.sHtMl

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://book.mzfgyi.asia/blog/1620332.sHtMl

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://book.mzfgyi.asia/blog/9700181.sHtMl

原标题：Practice：实现请求body重复读取中间件实践
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://book.mzfgyi.asia/blog/1906422.sHtMl

原标题：新手教程：gitstash暂存工作区变更实操
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://book.mzfgyi.asia/blog/9882987.sHtMl

原标题：golang 系统设计日志规范结构化日志落地
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://book.mzfgyi.asia/blog/5217504.sHtMl

原标题：golang k8s 日志收集 efk 简单架构
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://book.mzfgyi.asia/blog/3288104.sHtMl

原标题：K8s 镜像拉取网络故障修复
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://book.mzfgyi.asia/blog/5540155.sHtMl

原标题：排错：打包后资源路径，开发生产行为不一致
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://book.mzfgyi.asia/blog/5480445.sHtMl

原标题：前端组件库按需加载性能优化
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://book.mzfgyi.asia/blog/7042205.sHtMl

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://book.mzfgyi.asia/blog/5792633.sHtMl

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://book.mzfgyi.asia/blog/2328070.sHtMl

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://book.mzfgyi.asia/blog/8165154.sHtMl

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://book.mzfgyi.asia/blog/9490436.sHtMl

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://book.mzfgyi.asia/blog/1224800.sHtMl

原标题：方案设计：高可用Redis集群架构选型对比
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://book.mzfgyi.asia/blog/5012761.sHtMl

原标题：Hands‑on：模板渲染引擎最小原型实现
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.mzfgyi.asia/blog/0110636.sHtMl

原标题：golang nginx 反向代理 go 服务配置
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.mzfgyi.asia/blog/5011032.sHtMl

原标题：Hands‑on：简易代理服务器开发实践
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://book.mzfgyi.asia/blog/0780940.sHtMl

原标题：golang 系统设计灰度发布实现思路
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.mzfgyi.asia/blog/8420617.sHtMl

原标题：记一次日志切割脚本错误直接清空业务日志
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.mzfgyi.asia/blog/1834165.sHtMl

原标题：golang 系统设计 rest http 方法使用原则
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://book.mzfgyi.asia/blog/5987265.sHtMl

原标题：golang 信号量控制并发数量
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.mzfgyi.asia/blog/9844573.sHtMl


二、踩坑排错｜Troubleshooting
原标题：Hands‑on：简易网关路由转发组件开发
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://book.mzfgyi.asia/blog/0236519.sHtMl

原标题：golang 系统设计 mq 消息积压解决方案
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.mzfgyi.asia/blog/1845611.sHtMl

原标题：golang docker 镜像体积优化技巧
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://book.mzfgyi.asia/blog/9160433.sHtMl

原标题：git stash 代码暂存切换分支
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://book.mzfgyi.asia/blog/8840788.sHtMl

原标题：golang 熔断降级简易组件开发
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://book.mzfgyi.asia/blog/2018821.sHtMl

原标题：上传接口跨域配置特殊适配
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://book.mzfgyi.asia/blog/8531252.sHtMl

原标题：golang 系统设计结构化日志字段规范约定
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://book.mzfgyi.asia/blog/4604221.sHtMl

原标题：golang redis 缓存预热实现思路
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://book.mzfgyi.asia/blog/0103039.sHtMl

原标题：golang grpc protobuf 开发实操
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://book.mzfgyi.asia/blog/8491526.sHtMl

原标题：golang 文件上传下载接口开发
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://book.mzfgyi.asia/blog/6742537.sHtMl

原标题：Practice：实现多级缓存本地缓存+Redis实践
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://book.mzfgyi.asia/blog/1006711.sHtMl

原标题：CI/CD 流水线自动构建部署落地
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://book.mzfgyi.asia/blog/0262816.sHtMl

原标题：记一次第三方SDK版本兼容引发线上故障
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://book.mzfgyi.asia/blog/0387801.sHtMl

原标题：golang 系统设计接口防刷 ip 限流实现
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.mzfgyi.asia/blog/5519560.sHtMl

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://book.mzfgyi.asia/blog/4136197.sHtMl

原标题：Practice：实现简单信号处理优雅停机实践
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://book.mzfgyi.asia/blog/9550595.sHtMl

原标题：文件描述符优化进程卡死修复
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://book.mzfgyi.asia/blog/4280768.sHtMl

原标题：Performance：数据库join优化，大表join规避
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://book.mzfgyi.asia/blog/8543684.sHtMl

原标题：Practice：实现简单信号处理优雅停机实践
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://book.mzfgyi.asia/blog/7201383.sHtMl

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://book.mzfgyi.asia/blog/2243024.sHtMl

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://book.mzfgyi.asia/blog/2443450.sHtMl

原标题：调优方案：Nginx性能参数调优高并发配置
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://book.mzfgyi.asia/blog/0468657.sHtMl

原标题：golang 分布式锁 redis 实现
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://book.mzfgyi.asia/blog/8824429.sHtMl

原标题：golang 系统设计数据库死锁分析规避
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://book.mzfgyi.asia/blog/1599244.sHtMl

原标题：模拟登录鉴权权限判断示例
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://book.mzfgyi.asia/blog/9080795.sHtMl

原标题：golang 系统设计延迟消息实现几种方案对比
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://book.mzfgyi.asia/blog/0042702.sHtMl

原标题：主干开发团队代码合并策略
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://book.mzfgyi.asia/blog/4177838.sHtMl

原标题：开发复盘：大事务拆分优化业务性能实践
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://book.mzfgyi.asia/blog/3681828.sHtMl

原标题：开发记录：跨域中间件完整配置与边界处理
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://book.mzfgyi.asia/blog/6138846.sHtMl

原标题：golang 系统设计架构图绘图工具选型对比
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://book.mzfgyi.asia/blog/4483944.sHtMl

原标题：golang websocket 消息广播实现
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://book.mzfgyi.asia/blog/3443450.sHtMl

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://book.mzfgyi.asia/blog/8282715.sHtMl

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://book.mzfgyi.asia/blog/1569898.sHtMl

原标题：零基础理解版本控制核心概念与工作流
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://book.mzfgyi.asia/blog/1461400.sHtMl

原标题：数值类型溢出错乱问题修复
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://book.mzfgyi.asia/blog/1394501.sHtMl

原标题：golang 系统设计单元测试编写原则最佳实践
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://book.mzfgyi.asia/blog/3825179.sHtMl

原标题：golang websocket 消息广播实现
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://book.mzfgyi.asia/blog/0765349.sHtMl

原标题：排错：静态资源404，打包路径配置错误
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://book.mzfgyi.asia/blog/5682701.sHtMl

原标题：部署实践：HTTPS证书自动续期配置实践
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://book.mzfgyi.asia/blog/5613787.sHtMl

原标题：golang 系统设计延迟队列业务实现
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://book.mzfgyi.asia/blog/5446261.sHtMl

三、实战开发｜Practice
原标题：Practice：实现请求重试组件支持退避策略
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://book.mzfgyi.asia/blog/6668836.sHtMl

原标题：安全组端口开放网络访问
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://book.mzfgyi.asia/blog/6035206.sHtMl

原标题：WSL 内存上限限制防止资源耗尽
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://book.mzfgyi.asia/blog/1628763.sHtMl

原标题：Mock 接口服务快速搭建实操
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://book.mzfgyi.asia/blog/8513500.sHtMl

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://book.mzfgyi.asia/blog/1225569.sHtMl

原标题：golang 系统设计消息 partition 数量设置思路
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://book.mzfgyi.asia/blog/3597069.sHtMl

原标题：golang 系统设计读写分离延迟业务兼容
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://book.mzfgyi.asia/blog/3263950.sHtMl

原标题：设计思考：业务系统中什么时候不要用微服务
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://book.mzfgyi.asia/blog/6339056.sHtMl

原标题：设计思考：系统容量评估架构前期估算思路
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://book.mzfgyi.asia/blog/4829455.sHtMl

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://book.mzfgyi.asia/blog/5203138.sHtMl

原标题：golang docker 部署 kafka 本地调试
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://book.mzfgyi.asia/blog/8818160.sHtMl

原标题：调优方案：CDN优化静态资源访问延迟
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://book.mzfgyi.asia/blog/8132852.sHtMl

原标题：运维笔记：线上服务健康检查脚本编写
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://book.mzfgyi.asia/blog/6805034.sHtMl

原标题：包管理器依赖缓存清理
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.mzfgyi.asia/blog/2182985.sHtMl

原标题：AI实践：大模型生成代码后审查与重构实践
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.mzfgyi.asia/blog/6344993.sHtMl

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://book.mzfgyi.asia/blog/4632045.sHtMl

原标题：缓存过期打散防止缓存雪崩
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://book.mzfgyi.asia/blog/9349895.sHtMl

原标题：golang mysql json 字段查询使用
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://book.mzfgyi.asia/blog/4182346.sHtMl

原标题：golang 系统设计字段命名类型选择最佳实践
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://book.mzfgyi.asia/blog/3573315.sHtMl

原标题：golang docker compose 完整语法
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://book.mzfgyi.asia/blog/1730902.sHtMl

原标题：Hands‑on：简易验证码生成校验后端实践
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://book.mzfgyi.asia/blog/8063693.sHtMl

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://book.mzfgyi.asia/blog/4700471.sHtMl

原标题：golang etcd 分布式锁实现原理
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.mzfgyi.asia/blog/8614544.sHtMl

原标题：入门实践：实现简单文件读写功能
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://book.mzfgyi.asia/blog/3752745.sHtMl

原标题：主干开发团队代码合并策略
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.mzfgyi.asia/blog/1784906.sHtMl

原标题：golang 系统设计令牌桶漏桶算法对比
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://book.mzfgyi.asia/blog/4686712.sHtMl

原标题：性能笔记：HTTP连接复用性能优化实践
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://book.mzfgyi.asia/blog/8502651.sHtMl

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://book.mzfgyi.asia/blog/4090604.sHtMl

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://book.mzfgyi.asia/blog/8900452.sHtMl

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://book.mzfgyi.asia/blog/0420164.sHtMl

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://book.mzfgyi.asia/blog/9491775.sHtMl

原标题：入门实战：搭建简易静态网页项目
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://book.mzfgyi.asia/blog/8909439.sHtMl

原标题：golang redis bitmap 位图统计实现
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://book.mzfgyi.asia/blog/0082851.sHtMl

原标题：golang ci 流水线单元测试集成测试
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://book.mzfgyi.asia/blog/5565087.sHtMl

原标题：开发复盘：统一错误码体系设计落地实践
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://book.mzfgyi.asia/blog/6013391.sHtMl

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://book.mzfgyi.asia/blog/9058758.sHtMl

原标题：快速入门ORM，实现简单数据库增删改查
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://book.mzfgyi.asia/blog/8599567.sHtMl

原标题：golang 系统设计配置回滚版本历史记录实现
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://book.mzfgyi.asia/blog/0348874.sHtMl

原标题：golang yaml 解析配置加载实操
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.mzfgyi.asia/blog/5832476.sHtMl

原标题：golang 系统设计多租户数据隔离方案
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://book.mzfgyi.asia/blog/6182605.sHtMl

四、架构设计｜Architecture
原标题：golang 系统设计接口超时设计原则梳理
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://book.mzfgyi.asia/blog/3603526.sHtMl

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.mzfgyi.asia/blog/6709354.sHtMl

原标题：golang minio 预签名 url 临时访问
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://book.mzfgyi.asia/blog/5680594.sHtMl

原标题：架构笔记：高并发系统核心设计思路总结
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://book.mzfgyi.asia/blog/7945907.sHtMl

原标题：golang 系统设计技术方案文档模板参考
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://book.mzfgyi.asia/blog/4293996.sHtMl

原标题：服务熔断防止故障级联传播
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://book.mzfgyi.asia/blog/5972278.sHtMl

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://book.mzfgyi.asia/blog/5633578.sHtMl

原标题：golang ci 流水线漏洞扫描依赖检查
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://book.mzfgyi.asia/blog/6748825.sHtMl

原标题：开发测试生产多环境配置区分
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.mzfgyi.asia/blog/4254271.sHtMl

原标题：golang 系统设计技术文档维护更新最佳实践
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://book.mzfgyi.asia/blog/6863163.sHtMl

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.mzfgyi.asia/blog/0907132.sHtMl

原标题：golang 系统设计 webhook 回调处理架构
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://book.mzfgyi.asia/blog/3146435.sHtMl

原标题：golang 系统设计本地缓存与分布式缓存
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://book.mzfgyi.asia/blog/4289934.sHtMl

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.mzfgyi.asia/blog/3490600.sHtMl

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://book.mzfgyi.asia/blog/8668211.sHtMl

原标题：零基础理解跨域问题产生原因与基础方案
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://book.mzfgyi.asia/blog/5529612.sHtMl

原标题：快速上手简易网关转发逻辑模拟
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://book.mzfgyi.asia/blog/1350195.sHtMl

原标题：消息队列消费堆积扩容处理
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://book.mzfgyi.asia/blog/3773643.sHtMl

?
