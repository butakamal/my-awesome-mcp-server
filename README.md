# My Awesome MCP Server

このMCPサーバーは、［電卓機能］を提供します。

## 使い方

1. リポジトリをクローン：

　 git clone https://github.com/butakamal/calculator_server.git  
     cd calculator_server  
     uv sync  
  
2. Claude Desktop設定：  
  
　 {  
　　 "mcpServers": {  
         "calculator_server": {  
         "command": "uv",  
         "args": ["--directory", "/path/to/calculator_server", "run", "python", "calculator_server.py"]  
        }  
      }  
    }  
  
## 利用可能なツール  
  
| ツール名 | 説明 |  
|---------|------|  
| your_tool | 〇〇処理を実行 |  
| another_tool | △△データを分析 |  
  
## ライセンス  
  
MIT License  
