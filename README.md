![Sync Status](https://github.com/qinglanorg/Qinglan-AI-News/actions/workflows/main.yml/badge.svg)
# Qinglan-AI-News
青岚加密课堂新闻：基于 AI 自动化的 Web3 每日脱水情报站。日处理 300+ 信息源，只留 10 条真干货。
# 青岚新闻 (Qinglan AI News) 🤖

**AI 驱动的 Web3 信息脱水情报站。** 每日自动处理 300+ 行业新闻，利用 LLM 实现精炼摘要与深度简评。

## 🔗 官方渠道
- **实时快讯官网**: [https://qinglan.org/24news/](https://qinglan.org/24news/)
- **Telegram 群组**: [青岚免费交易社群](https://t.me/btcqing123)

## 📊 运行示例 (2026-01-08)
![青岚加密课堂早报示例]
<img width="480" height="1121" alt="image" src="https://github.com/user-attachments/assets/4fa2599d-783b-4020-9cda-958d7f5e2499" />


## 🛠 技术路线
- **抓取层**: Python + BeautifulSoup + Playwright
- **处理层**: LangChain + GPT-4o-mini (向量去重)
- **分发层**: Telegram Bot API + GitHub Actions
