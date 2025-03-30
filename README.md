# flow3-bot

Flow3Master - 智能自动化助手

注册链接: [Flow3 Dashboard](https://dashboard.flow3.tech?ref=wExZnVipv)  
下载扩展: [Flow3 Extension](https://chromewebstore.google.com/detail/flow3/lhmminnoafalclkgcbokfcngkocoffcp)

## 功能特点

  - **自动获取账户统计信息**：实时显示带宽、总计、邀请和任务积分。
  - **自动每日签到**
  - **自动完成任务**
  - **每分钟自动 Ping**
  - **多账户并发支持**

## 系统要求

- 已安装 Python 3.9 或更高版本，并配置好 pip。

## 安装步骤

1. **克隆仓库：**
```bash
  git clone https://github.com/ziqing888/flow3-bot.git
  cd flow3-bot 
```
安装依赖：
```bash
pip install aiohttp pynacl base58 colorama pytz
```
配置说明
accounts.txt：
在项目目录中 accounts.txt，填入 Solana 私钥，每行一个。示例：
```bash
  your_private_key_1
  your_private_key_2
```
proxy.txt（可选）：
在项目目录中创建 proxy.txt，填入代理地址，每行一个。示例：
```bash
  192.168.1.1:8080  # 默认 HTTP
  http://user:pass@10.0.0.1:3128
```



