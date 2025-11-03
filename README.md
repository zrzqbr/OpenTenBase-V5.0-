# OpenTenBase-V5.0-
openEuler 22.03-LTS-SP4 部署 OpenTenBase V5.0 并集成 AI 能力全流程验证完成。OpenTenBase 作为高可靠、可横向扩展的分布式关系型数据库，采用清晰的 “GTM+CN+DN” 架构，普通 x86 设备即可搭建集群。 实操中先从源码编译起步，完成单机集群初始化与启动。通过明确 GTM（全局事务管理）、CN（协调节点）、DN（数据节点）的角色分工及端口配置，顺利解决组件间通信基础问题。 核心验证 opentenbase_ai 插件集成流程，该插件依赖 pgsql-http 扩展，可快速实现 SQL 与 AI 模型对接。其对腾讯混元、DeepSeek 等国产大模型兼容性优异，无需复杂代码开发，即可便捷调用 AI 能力。
