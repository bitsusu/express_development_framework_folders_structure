│   ├── utils/               # 工具函数层：全局通用工具，纯函数、无业务侵入，可复用 ✅
│   │   ├── db-util.js       # MySQL8.0工具封装：连接池、事务、统一SQL执行、错误处理（核心工具）
│   │   ├── res-util.js      # 统一响应格式封装：成功、失败、分页、异常的统一返回体
│   │   ├── jwt-util.js      # JWT工具：生成token、验证token、刷新token（登录鉴权必备）
│   │   ├── log-util.js      # 日志工具：封装winston，区分info/error/warn/debug
│   │   ├── validate-util.js # 参数校验工具：封装joi/express-validator，统一校验请求参数
│   │   └── index.js         # 工具统一导出
