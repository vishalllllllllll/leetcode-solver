# LeetCode Telegram Bot (n8n + GPT-4o-mini)

This is an automated Telegram bot built with n8n and OpenAI that:

- Sends the LeetCode daily challenge (updates everyday)
- Generates solutions using GPT-4o-mini
- Tests them with Piston API and matches with expected o/p with actual o/p
- Runs with testcases
- Supports only on-demand usage

## 📦 Stack
- n8n (automation engine)
- Telegram Bot API
- OpenAI (GPT-4o-mini)
- Piston (code execution)
- LeetCode GraphQL

## 🚀 Features
- 📅 Daily challenge auto-push
- 💬 Telegram trigger for on-demand solve
- 🧠 GPT-powered solutions
- 🧪 Live testing with expected output comparison

## 🛠 Setup
1. Import `leetcode-solver.json` into n8n
2. Add your telegram bot using '@botfather'
3. Add OpenAI + Piston + telegram bot credentials
4. Activate the workflow

## 🔗 Credits
Built by [VISHAL M]
