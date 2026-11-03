一个MCP Server的核心是向客户端暴露三类原语（Primitives）:
- 有哪些可以执行的**工具（Tools）**  
- 取的**资源（Resources）**  
- 以引导用户的**提示模板（Prompts）**  

通信协议：  
	**JSON-RPC over 有状态会话**。支持 stdio（本地）或 HTTP/SSE（远程），连接有完整的生命周期（初始化、协商、关闭）

go库  
github.com/modelcontextprotocol/go-sdk/mcp  
python库  
https://github.com/PrefectHQ/fastmcp  
typeScript库  
https://github.com/punkpeye/fastmcp  