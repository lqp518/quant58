# Quant58 — 多交易所量化交易平台

**6大交易所 · 策略加密保护 · 实时看板 · 极低成本部署**

## 支持交易所

Binance、OKX、Bybit、Bitget、Gate.io、MEXC，现货 + 合约全覆盖

## 支持策略语言

JavaScript / PineScript / C++ /My语言 /Python

## 平台特色

- **策略加密** — 代码编译为二进制下发，保护策略不被破解
- **实时看板** — 资产快照、权益曲线、交易信号、运行日志秒级推送
- **多交易所统一管理** — 一个平台管理全部交易所账户，一站式操作
- **深度回测** — 历史 K 线精准回测，验证策略有效性
- **金融级审计** — 每笔交易、每条日志可追溯，平台与用户权责清晰
- **极低成本** — 单台服务器即可运行，免去高昂云服务费用

---

## 部署

Docker 一键部署：

```bash
docker pull quant58com/quant58com:latest
docker run -d --name quant58 \
  -e ROBOT_SERVER_URL="bot.quant58.com/your_id" \
  -e ROBOT_PASSWORD="your_password" \
  quant58com/quant58com:latest
```

[Docker Hub]https://hub.docker.com/r/quant58com/quant58com 

Linux maxos windows
[控制台部署说明]https://www.quant58.com/w/nodes?view=add

---

Copyright © 2026 Quant58.com All rights reserved.
本仓库仅作项目介绍，源代码不公开。
