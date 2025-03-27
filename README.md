# Weather MCP Server

基于@modelcontextprotocol/sdk实现的一个纯TS实现的天气查询MCP server

## 基本思路

1. 使用 McpServer 类创建服务器实例
2. 通过 server.tool() 注册工具
3. 使用 zod 进行参数验证
4. 返回标准化的响应格式
