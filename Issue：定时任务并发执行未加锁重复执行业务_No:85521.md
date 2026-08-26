最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://wiki.9jnxlh.asia/arts/766222.Doc

原标题：golang 开发环境快速搭建指南
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.9jnxlh.asia/arts/896992.Doc

原标题：Hands‑on：本地模拟消息重复消费处理实践
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.9jnxlh.asia/arts/173182.Doc

原标题：新手向：npm/pip/maven依赖版本冲突入门排查
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.9jnxlh.asia/arts/495516.Doc

原标题：实践：Git工作流主干开发团队协作实践
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.9jnxlh.asia/arts/358432.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.9jnxlh.asia/arts/378434.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.9jnxlh.asia/arts/288128.Doc

原标题：golang redis stream 消息队列实践
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://wiki.9jnxlh.asia/arts/413987.Doc

原标题：nodejs 多进程任务分发处理
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://wiki.9jnxlh.asia/arts/762170.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.9jnxlh.asia/arts/839442.Doc

原标题：golang 系统设计指标聚合计算存储选型对比
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.9jnxlh.asia/arts/751047.Doc

原标题：golang 容器健康检查接口开发
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.9jnxlh.asia/arts/400371.Doc

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://wiki.9jnxlh.asia/arts/704359.Doc

原标题：golang 令牌桶限流中间件 gin
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.9jnxlh.asia/arts/458615.Doc

原标题：golang 系统设计日志检索排查线上问题实操技巧
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.9jnxlh.asia/arts/688681.Doc

原标题：Nginx 缓冲区调优大文件上传
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.9jnxlh.asia/arts/239839.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.9jnxlh.asia/arts/377455.Doc

原标题：golang 系统设计错误码体系完整设计
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.9jnxlh.asia/arts/411100.Doc

原标题：设计思考：业务系统如何做故障隔离架构
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://wiki.9jnxlh.asia/arts/158869.Doc

原标题：golang 定时任务 cron 使用指南
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://wiki.9jnxlh.asia/arts/946970.Doc

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://wiki.9jnxlh.asia/arts/048285.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.9jnxlh.asia/arts/367150.Doc

原标题：前端静态缓存更新生效处理
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://wiki.9jnxlh.asia/arts/742570.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.9jnxlh.asia/arts/798468.Doc

原标题：golang minio 预签名 url 临时访问
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.9jnxlh.asia/arts/426595.Doc

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.9jnxlh.asia/arts/467834.Doc

原标题：GitHub 项目提交推送完整流程讲解
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.9jnxlh.asia/arts/503233.Doc

原标题：调优方案：静态资源缓存头Cache‑Control优化
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://wiki.9jnxlh.asia/arts/649140.Doc

原标题：golang 数据库连接泄露排查
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.9jnxlh.asia/arts/814580.Doc

原标题：分页逻辑错误数据漏查修复
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.9jnxlh.asia/arts/672106.Doc

原标题：golang 系统设计指标聚合计算存储选型对比
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://wiki.9jnxlh.asia/arts/182873.Doc

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.9jnxlh.asia/arts/539076.Doc

原标题：安全实践：备份文件访问权限安全管控
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.9jnxlh.asia/arts/366538.Doc

原标题：安全复盘：日志打印敏感信息泄露治理
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.9jnxlh.asia/arts/757633.Doc

原标题：架构笔记：业务操作审计日志系统架构设计
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://wiki.9jnxlh.asia/arts/540367.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://wiki.9jnxlh.asia/arts/300940.Doc

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.9jnxlh.asia/arts/672514.Doc

原标题：运维笔记：系统监控指标大盘搭建实操
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://wiki.9jnxlh.asia/arts/600689.Doc

原标题：golang 重试退避机制代码实现
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.9jnxlh.asia/arts/528466.Doc

原标题：golang 系统设计 mq 消息丢失完整防护
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.9jnxlh.asia/arts/241360.Doc


二、踩坑排错｜Troubleshooting
原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/963628.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://wiki.9jnxlh.asia/arts/040912.Doc

原标题：无用对象回收抑制内存上涨
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.9jnxlh.asia/arts/729694.Doc

原标题：golang gorm 预加载关联查询优化
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.9jnxlh.asia/arts/835835.Doc

原标题：前端国际化多语言方案落地
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/860032.Doc

原标题：golang redis 缓存击穿防护实现
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.9jnxlh.asia/arts/844916.Doc

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://wiki.9jnxlh.asia/arts/205127.Doc

原标题：HTTP 状态码请求头完整梳理
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.9jnxlh.asia/arts/270536.Doc

原标题：Practice：实现请求body重复读取中间件实践
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.9jnxlh.asia/arts/674658.Doc

原标题：golang 系统设计技术文档编写最佳实践
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://wiki.9jnxlh.asia/arts/790658.Doc

原标题：多套环境灵活切换配置方案
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.9jnxlh.asia/arts/882738.Doc

原标题：动态定时任务业务调度实现
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://wiki.9jnxlh.asia/arts/040253.Doc

原标题：golang 系统信号信号量处理
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/186731.Doc

原标题：多规则数据脱敏组件开发
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.9jnxlh.asia/arts/256248.Doc

原标题：golang http 代理客户端配置
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://wiki.9jnxlh.asia/arts/828731.Doc

原标题：golang 系统设计消息重试次数间隔策略设置
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.9jnxlh.asia/arts/298331.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.9jnxlh.asia/arts/118659.Doc

原标题：golang 消息队列 kafka 消费开发
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.9jnxlh.asia/arts/718747.Doc

原标题：快速上手简易网关转发逻辑模拟
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.9jnxlh.asia/arts/133957.Doc

原标题：golang ci 流水线单元测试集成测试
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://wiki.9jnxlh.asia/arts/959288.Doc

原标题：安全实践：最小权限原则数据库账号管控
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.9jnxlh.asia/arts/269882.Doc

原标题：5分钟快速搭建个人技术文档站点
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.9jnxlh.asia/arts/028116.Doc

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://wiki.9jnxlh.asia/arts/713223.Doc

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.9jnxlh.asia/arts/992223.Doc

原标题：Architecture：鉴权授权系统架构设计思路
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.9jnxlh.asia/arts/340607.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://wiki.9jnxlh.asia/arts/511622.Doc

原标题：golang 系统设计指标聚合计算存储选型对比
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://wiki.9jnxlh.asia/arts/428236.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://wiki.9jnxlh.asia/arts/419320.Doc

原标题：golang 系统设计数据库基准压测简单思路
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://wiki.9jnxlh.asia/arts/314353.Doc

原标题：坑点：npm/pip全局版本与项目本地版本冲突
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://wiki.9jnxlh.asia/arts/425886.Doc

原标题：HTTPS 证书过期更新操作
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.9jnxlh.asia/arts/509400.Doc

原标题：golang 系统设计配置回滚版本历史记录实现
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.9jnxlh.asia/arts/790286.Doc

原标题：golang redis 事务 multi exec 使用
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.9jnxlh.asia/arts/314414.Doc

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/542661.Doc

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.9jnxlh.asia/arts/703841.Doc

原标题：golang github actions 完整工作流示例
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.9jnxlh.asia/arts/559811.Doc

原标题：Redis 内存淘汰策略数据防丢失
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.9jnxlh.asia/arts/251353.Doc

原标题：坑点：gitcherry‑pick引入不兼容代码
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/598069.Doc

原标题：SDK 版本兼容线上崩溃修复
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.9jnxlh.asia/arts/485413.Doc

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.9jnxlh.asia/arts/721380.Doc

三、实战开发｜Practice
原标题：golang zap 日志按日期切割方案
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.9jnxlh.asia/arts/269516.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://wiki.9jnxlh.asia/arts/839557.Doc

原标题：golang kafka 消费者偏移量管理
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.9jnxlh.asia/arts/263215.Doc

原标题：一次数据库死锁现场分析与解决方案记录
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.9jnxlh.asia/arts/428847.Doc

原标题：CORS 跨域问题多种解决方案
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.9jnxlh.asia/arts/569926.Doc

原标题：golang 结构体深拷贝几种实现
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://wiki.9jnxlh.asia/arts/081810.Doc

原标题：golang 系统设计 README 开源文档模板
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.9jnxlh.asia/arts/348769.Doc

原标题：设计思考：系统幂等性整体架构层面保障
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.9jnxlh.asia/arts/677742.Doc

原标题：golang 系统设计网关路由规则动态配置实现
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.9jnxlh.asia/arts/841743.Doc

原标题：Docker 网络模式容器互通设置
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.9jnxlh.asia/arts/261163.Doc

原标题：golang 系统设计故障预案编写模板参考示例
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/077662.Doc

原标题：文件监控服务自动重启开发
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.9jnxlh.asia/arts/119524.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.9jnxlh.asia/arts/233305.Doc

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.9jnxlh.asia/arts/673946.Doc

原标题：golang etcd 分布式锁实现原理
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.9jnxlh.asia/arts/373495.Doc

原标题：golang 布隆过滤器实现去重
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.9jnxlh.asia/arts/300270.Doc

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.9jnxlh.asia/arts/287195.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://wiki.9jnxlh.asia/arts/755735.Doc

原标题：golang 系统设计网关请求日志 traceId 透传实现
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.9jnxlh.asia/arts/237253.Doc

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.9jnxlh.asia/arts/821137.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://wiki.9jnxlh.asia/arts/655875.Doc

原标题：多实例部署 Session 共享方案
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.9jnxlh.asia/arts/081535.Doc

原标题：优化实践：多级缓存减少下游服务调用压力
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/077296.Doc

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://wiki.9jnxlh.asia/arts/083561.Doc

原标题：开发复盘：批量任务进度持久化实现方案
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.9jnxlh.asia/arts/638802.Doc

原标题：golang 系统设计文件存储选型对比
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://wiki.9jnxlh.asia/arts/791489.Doc

原标题：实战：Redis集群本地搭建与功能验证
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.9jnxlh.asia/arts/407669.Doc

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://wiki.9jnxlh.asia/arts/969752.Doc

原标题：实战项目：多实例部署会话一致性验证实践
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.9jnxlh.asia/arts/063590.Doc

原标题：安全笔记：CSP内容安全策略配置实践
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.9jnxlh.asia/arts/865434.Doc

原标题：静态博客部署 GitHub Pages 教程
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.9jnxlh.asia/arts/933874.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.9jnxlh.asia/arts/122390.Doc

原标题：golang redis pipeline 原子性说明
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://wiki.9jnxlh.asia/arts/196528.Doc

原标题：零基础理解前后端简单交互流程
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.9jnxlh.asia/arts/380228.Doc

原标题：后端登录鉴权模块完整开发
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.9jnxlh.asia/arts/602216.Doc

原标题：golang 系统设计 README 开源文档模板
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.9jnxlh.asia/arts/904016.Doc

原标题：golang 系统设计监控告警阈值设置思路
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.9jnxlh.asia/arts/717337.Doc

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.9jnxlh.asia/arts/966961.Doc

原标题：部署实践：Nginx高可用配置方案实践
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://wiki.9jnxlh.asia/arts/802588.Doc

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.9jnxlh.asia/arts/387903.Doc

四、架构设计｜Architecture
原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.9jnxlh.asia/arts/833730.Doc

原标题：golang 系统设计蓝绿发布滚动发布对比
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.9jnxlh.asia/arts/485406.Doc

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.9jnxlh.asia/arts/836664.Doc

原标题：golang 系统设计延迟队列业务实现
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.9jnxlh.asia/arts/135814.Doc

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.9jnxlh.asia/arts/350038.Doc

原标题：golang 系统设计异步化改造业务流程思路
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.9jnxlh.asia/arts/600331.Doc

原标题：golang 系统设计令牌桶漏桶算法对比
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.9jnxlh.asia/arts/411743.Doc

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.9jnxlh.asia/arts/592182.Doc

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.9jnxlh.asia/arts/736527.Doc

原标题：golang mongodb 索引优化查询速度
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://wiki.9jnxlh.asia/arts/927208.Doc

原标题：Architecture：文件处理服务架构大文件内存规避
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://wiki.9jnxlh.asia/arts/288475.Doc

原标题：golang 系统设计 json 解析性能优化实操
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/386019.Doc

原标题：跨平台换行符统一异常修复
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://wiki.9jnxlh.asia/arts/592558.Doc

原标题：golang mongodb 事务多文档使用
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.9jnxlh.asia/arts/459440.Doc

原标题：golang 系统设计分表分页排序业务实现难点
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://wiki.9jnxlh.asia/arts/670261.Doc

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://wiki.9jnxlh.asia/arts/640397.Doc

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/026853.Doc

原标题：开发环境变量配置全平台教程
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://wiki.9jnxlh.asia/arts/971079.Doc

?
