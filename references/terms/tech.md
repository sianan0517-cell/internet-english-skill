# 技术研发岗位术语

## 一、前端开发

| 术语 | 释义 | 例句 |
|------|------|------|
| SPA (Single Page Application) | 单页应用 | We rebuilt the app as an SPA for a smoother user experience. |
| SSR (Server-Side Rendering) | 服务端渲染 | SSR improves SEO and initial load performance. |
| CSR (Client-Side Rendering) | 客户端渲染 | CSR can make the first paint slower on slow networks. |
| Hydration | 水合/激活 | Hydration attaches event listeners to the server-rendered HTML. |
| PWA (Progressive Web App) | 渐进式网页应用 | PWA lets users install the web app on their home screen. |
| Responsive design | 响应式设计 | Responsive design adapts the layout to any screen size. |
| Component | 组件 | This button should be a reusable component. |
| State management | 状态管理 | We're using a centralized store for state management. |
| Virtual DOM | 虚拟 DOM | React uses a virtual DOM to minimize actual DOM updates. |
| Lazy loading | 懒加载 | Lazy loading reduces initial bundle size significantly. |
| Code splitting | 代码分割 | Code splitting lets us load features on demand. |
| Webpack / Vite / Rollup | 前端构建工具 | We migrated from Webpack to Vite for faster HMR. |
| Bundle size | 包体积 | We need to reduce the bundle size — it's over 500KB gzipped. |
| Tree shaking | 摇树优化 | Tree shaking removes unused code from the final bundle. |
| SEO (Search Engine Optimization) | 搜索引擎优化 | SSR is essential for SEO on content-heavy pages. |
| Accessibility / a11y | 无障碍设计 | Accessibility isn't optional — it's a legal requirement. |
| ARIA labels | 无障碍标签 | We need ARIA labels on all interactive elements. |
| Cross-browser compatibility | 跨浏览器兼容 | Cross-browser issues are a pain to debug. |
| Polyfill | 兼容填充代码 | We use polyfills to support older browsers. |
| Headless CMS | 无头 CMS | Headless CMS separates the content layer from the presentation. |

## 二、后端与架构

| 术语 | 释义 | 例句 |
|------|------|------|
| API (Application Programming Interface) | 应用程序接口 | We exposed the data through a RESTful API. |
| REST (Representational State Transfer) | REST 架构 | We follow REST principles for all our APIs. |
| GraphQL | 图查询语言 API | GraphQL lets clients request exactly the data they need. |
| gRPC | 高性能 RPC 框架 | We use gRPC for internal microservice communication. |
| Microservice | 微服务 | We're decomposing the monolith into microservices. |
| Monolith | 单体架构 | The monolith has become a bottleneck for team velocity. |
| Service mesh | 服务网格 | Istio is our service mesh for managing microservice traffic. |
| Message queue | 消息队列 | Messages are queued for async processing. |
| Kafka | 分布式消息队列 | We use Kafka for real-time event streaming. |
| Pub/Sub | 发布/订阅模式 | The notification service uses a pub/sub architecture. |
| Event-driven | 事件驱动 | We're moving to an event-driven architecture for better scalability. |
| CQRS (Command Query Responsibility Segregation) | 命令查询职责分离 | CQRS separates read and write operations for better performance. |
| Event sourcing | 事件溯源 | Event sourcing stores all state changes as a sequence of events. |
| Idempotent | 幂等的 | Make sure the endpoint is idempotent — it might be called twice. |
| Rate limiting | 速率限制 | We need rate limiting to prevent abuse. |
| Circuit breaker | 断路器 | The circuit breaker trips when the downstream service fails repeatedly. |
| Throttling | 限流 | We throttle requests to avoid overwhelming the database. |
| Load balancing | 负载均衡 | Load balancing distributes traffic across multiple servers. |
| Reverse proxy | 反向代理 | Nginx acts as a reverse proxy in front of our app servers. |
| API gateway | API 网关 | All traffic goes through the API gateway for auth and routing. |
| Backend-for-frontend (BFF) | 前后端适配层 | BFF patterns help us optimize API responses per client type. |

## 三、数据库

| 术语 | 释义 | 例句 |
|------|------|------|
| Relational database | 关系型数据库 | We use PostgreSQL as our primary relational database. |
| NoSQL | 非关系型数据库 | MongoDB is our NoSQL database for flexible schemas. |
| Schema | 数据库模式 | The schema needs to be updated to support the new feature. |
| Index | 索引 | Adding an index improved query performance by 10x. |
| Partition / Shard | 分区/分片 | We shard the users table by user_id for horizontal scaling. |
| ACID (Atomicity, Consistency, Isolation, Durability) | ACID 特性 | ACID guarantees ensure data integrity in transactions. |
| CAP theorem | CAP 定理 | CAP theorem states you can only guarantee two of three: consistency, availability, partition tolerance. |
| Replication | 复制 | We use primary-replica replication for read scaling. |
| Failover | 故障转移 | The failover kicked in automatically when the primary went down. |
| Read replica | 只读副本 | We offload read-heavy queries to the read replica. |
| Cache | 缓存 | Redis is our cache layer for frequently accessed data. |
| Cache invalidation | 缓存失效 | Cache invalidation is one of the hardest problems in distributed systems. |
| ORM (Object-Relational Mapping) | 对象关系映射 | We use an ORM to interact with the database from code. |
| Query optimization | 查询优化 | The query was slow — we added an index to fix it. |
| Deadlock | 死锁 | The transaction was blocked by a deadlock. |
| Connection pool | 连接池 | Connection pool settings control how many DB connections we maintain. |
| Data migration | 数据迁移 | We need a rollback plan for the data migration. |
| Backup | 备份 | Full backups run daily, incremental backups every hour. |
| Point-in-time recovery | 时间点恢复 | PITR lets us restore data to any moment in the past 30 days. |

## 四、DevOps 与云

| 术语 | 释义 | 例句 |
|------|------|------|
| CI/CD (Continuous Integration/Continuous Deployment) | 持续集成/持续部署 | Our CI/CD pipeline runs all tests before deployment. |
| Pipeline | 流水线 | The pipeline has stages: build, test, deploy. |
| GitOps | GitOps 运维 | We manage infrastructure as code using GitOps. |
| Container | 容器 | We containerize all our services with Docker. |
| Kubernetes / K8s | 容器编排平台 | The app runs on a Kubernetes cluster in the cloud. |
| Pod | K8s 最小调度单位 | The new pod will handle background job processing. |
| Helm chart | K8s 部署包 | We use Helm charts to manage Kubernetes deployments. |
| Auto-scaling | 自动扩缩容 | Auto-scaling adds pods when CPU utilization exceeds 70%. |
| Horizontal scaling | 水平扩展 | Horizontal scaling adds more instances of the service. |
| Vertical scaling | 垂直扩展 | Vertical scaling gives each instance more resources. |
| Deployment | 部署 | The deployment took 3 minutes with zero downtime. |
| Blue-green deployment | 蓝绿部署 | Blue-green deployment lets us switch traffic instantly. |
| Canary release | 金丝雀发布 | We route 5% of traffic to the new version first. |
| Rollback | 回滚 | The rollback was triggered within 2 minutes of detecting the issue. |
| Health check | 健康检查 | The health check endpoint reports service status. |
| Liveness probe | 存活探针 | K8s uses liveness probes to detect unresponsive containers. |
| SLA (Service Level Agreement) | 服务水平协议 | Our SLA guarantees 99.9% uptime. |
| SLO (Service Level Objective) | 服务水平目标 | The SLO for P99 latency is under 200ms. |
| Observability | 可观测性 | Observability includes metrics, logs, and traces. |
| Monitoring | 监控 | We use Prometheus and Grafana for monitoring. |
| Alert | 告警 | The alert fired at 3am — P99 latency exceeded 1 second. |
| Runbook | 运维手册 | The runbook says to restart the service and escalate if it recurs. |
| On-call | 值班 | We're rotating on-call duty across the team. |
| Cloud provider | 云服务商 | We use a mix of cloud providers for cost optimization. |
| IaaS (Infrastructure as a Service) | 基础设施即服务 | IaaS gives us virtual machines without managing hardware. |
| PaaS (Platform as a Service) | 平台即服务 | We use a PaaS to reduce ops overhead. |
| SaaS (Software as a Service) | 软件即服务 | The team uses several SaaS tools for collaboration. |
| Infrastructure as Code (IaC) | 基础设施即代码 | Terraform is our tool for infrastructure as code. |
| Immutable infrastructure | 不可变基础设施 | With immutable infra, we replace servers rather than patching them. |
| Configuration management | 配置管理 | We use configuration management tools to enforce consistency. |
| Technical debt | 技术债务 | We allocated 20% of sprint capacity to paying down tech debt. |

## 五、代码质量

| 术语 | 释义 | 例句 |
|------|------|------|
| Pull request (PR) | 合并请求 | I opened a PR for the new feature — please review. |
| Code review | 代码评审 | Code review catches bugs and spreads knowledge across the team. |
| Lint / Linting | 代码静态检查 | The linter caught 10 issues before the build. |
| Unit test | 单元测试 | Unit test coverage should be at least 80%. |
| Integration test | 集成测试 | Integration tests verify that components work together. |
| E2E test (End-to-End) | 端到端测试 | Playwright is our tool for E2E testing. |
| Test coverage | 测试覆盖率 | The test coverage report shows we're missing some branches. |
| Regression | 回归 | We had a regression — a feature from last sprint stopped working. |
| Hotfix | 热修复 | We pushed a hotfix to production last night. |
| Bug | 缺陷 | We found a critical bug in the payment flow. |
| Debug | 调试 | Let's debug this together — I can't reproduce it locally. |
| Stack trace | 调用栈 | The stack trace points to a null pointer exception. |
| Profiling | 性能分析 | Profiling shows the bottleneck is in the database query. |
| Performance optimization | 性能优化 | Performance optimization reduced p99 latency by 40%. |
| Refactor | 重构 | We need to refactor this module — it's become a mess. |
| DRY (Don't Repeat Yourself) | 不要重复自己 | DRY is a principle, not a rule — sometimes duplication is fine. |
| SOLID principles | SOLID 原则 | We try to follow SOLID principles in our code design. |
| Code smell | 代码坏味道 | Long methods are a code smell — they need refactoring. |
| Technical review | 技术评审 | The architecture change needs a technical review. |
| Pair programming | 结对编程 | Pair programming helps catch issues early and spread knowledge. |

## 六、安全

| 术语 | 释义 | 例句 |
|------|------|------|
| Authentication | 身份认证 | We use OAuth 2.0 for authentication. |
| Authorization | 权限控制 | Authorization determines what authenticated users can access. |
| OAuth 2.0 | 开放授权协议 | OAuth 2.0 lets users grant third-party apps access without sharing passwords. |
| JWT (JSON Web Token) | JSON 网络令牌 | JWTs are used to authenticate API requests. |
| MFA (Multi-Factor Authentication) | 多因素认证 | MFA is required for all internal system access. |
| Encryption | 加密 | All data in transit is encrypted with TLS 1.3. |
| HTTPS | 安全超文本传输协议 | We enforce HTTPS everywhere — no exceptions. |
| CSRF (Cross-Site Request Forgery) | 跨站请求伪造 | CSRF tokens prevent cross-site request forgery attacks. |
| XSS (Cross-Site Scripting) | 跨站脚本攻击 | Sanitizing user input prevents XSS attacks. |
| SQL injection | SQL 注入 | Parameterized queries prevent SQL injection. |
| Secrets management | 密钥管理 | We use a secrets manager — never commit credentials to Git. |
| Vulnerability scan | 漏洞扫描 | The vulnerability scan found three high-severity issues. |
| Penetration test / Pen test | 渗透测试 | An annual pen test is part of our security audit. |
| Zero trust | 零信任安全 | We're moving to a zero-trust security model. |
| RBAC (Role-Based Access Control) | 基于角色的权限控制 | RBAC makes it easy to manage permissions at scale. |
