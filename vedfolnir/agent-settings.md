## 配置参数说明
|  环境变量名   | 默认值  |说明  | 是否必须  |
|  ----  | ----  |---- |----  |
| VEDFOLNIR_WS_DELAY  | 10 s | 探针启动后，与 vedfolnir-manager 连接初始化延迟  |否  |
| VEDFOLNIR_PROMETHEUS_PORT | 8888 | metrics 端口号  | 否  |
| VEDFOLNIR_IS_EXPOSE_PROMETHEUS  | false | 是否需要暴露 metrics 接口  | 否  |
| VEDFOLNIR_SERVER_URL  |  | vedfolnir-manager url | 是  |
| AGENT_INSTANCE_ID  |  | 实例 id  | 是  |
| AGENT_NAME  |  | 当前实例服务名  | 是  |
| DMP_ENVIRONMENT_CODE  |  | 当前实例所在环境 Code  | 是  |