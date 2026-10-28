<div align="center">

<a href="https://ebtekarai.ir"><img src="https://raw.githubusercontent.com/EbtekarAi/ebtekar-ai/main/assets/banner.png" alt="Ebtekar AI" width="100%"></a>

### سلام! 👋 ما **ابتکار** هستیم
پلتفرم هوش مصنوعی فارسی؛ همهٔ مدل‌های برتر دنیا با یک حساب، یک کیف پول و یک API

**Hi! We're Ebtekar**, a Persian-first AI platform: every frontier model with one account, one wallet and one API.

<br>

<img src="https://raw.githubusercontent.com/EbtekarAi/ebtekar-ai/main/assets/models/openai.png" width="42" title="ChatGPT">&nbsp;
<img src="https://raw.githubusercontent.com/EbtekarAi/ebtekar-ai/main/assets/models/claude.png" width="42" title="Claude">&nbsp;
<img src="https://raw.githubusercontent.com/EbtekarAi/ebtekar-ai/main/assets/models/gemini.png" width="42" title="Gemini">&nbsp;
<img src="https://raw.githubusercontent.com/EbtekarAi/ebtekar-ai/main/assets/models/grok.png" width="42" title="Grok">&nbsp;
<img src="https://raw.githubusercontent.com/EbtekarAi/ebtekar-ai/main/assets/models/deepseek.png" width="42" title="DeepSeek">&nbsp;
<img src="https://raw.githubusercontent.com/EbtekarAi/ebtekar-ai/main/assets/models/kimi.png" width="42" title="Kimi">&nbsp;
<img src="https://raw.githubusercontent.com/EbtekarAi/ebtekar-ai/main/assets/models/perplexity.png" width="42" title="Perplexity">&nbsp;
<img src="https://raw.githubusercontent.com/EbtekarAi/ebtekar-ai/main/assets/models/meta.png" width="42" title="Llama">&nbsp;
<img src="https://raw.githubusercontent.com/EbtekarAi/ebtekar-ai/main/assets/models/nanobanana.png" width="42" title="Nano Banana">&nbsp;
<img src="https://raw.githubusercontent.com/EbtekarAi/ebtekar-ai/main/assets/models/kling.png" width="42" title="Kling">

<sub>+70 models · 12 families · text · code · image · video · speech</sub>

<br><br>

[![Website](https://img.shields.io/badge/ebtekarai.ir-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white)](https://ebtekarai.ir)
[![Developer guide](https://img.shields.io/badge/Developer%20Guide-38E8FF?style=for-the-badge&logo=readthedocs&logoColor=0A0D1C)](https://github.com/EbtekarAi/ebtekar-ai/blob/main/docs/developers.md)
[![Persian Guide](https://img.shields.io/badge/Persian%20Guide-4F46E5?style=for-the-badge&logo=readthedocs&logoColor=white)](https://github.com/EbtekarAi/ebtekar-ai/blob/main/docs/developers.fa.md)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/EbtekarAi)

</div>

---

### 🧭 Products · محصولات

<table>
<tr>
<td width="25%" valign="top" align="center">

🌐<br>**Web app**<br><sub>Chat with 70+ models, Python in the browser, cited web search, documents & memory</sub><br><sub dir="rtl">چت با بیش از ۷۰ مدل، پایتون در مرورگر، وب‌سرچ مستند</sub>

</td>
<td width="25%" valign="top" align="center">

🖥️<br>**Ebtekar for Windows**<br><sub>An interactive island with Ebtekarak, your companion</sub><br><sub dir="rtl">نوار تعاملی با همراهی به اسم ابتکارک</sub>

</td>
<td width="25%" valign="top" align="center">

🔌<br>**Developer Gateway**<br><sub>One key, every model. Anthropic Messages–compatible</sub><br><sub dir="rtl">یک کلید برای همهٔ مدل‌ها، سازگار با Anthropic</sub>

</td>
<td width="25%" valign="top" align="center">

📱<br>**Mobile**<br><sub>On <a href="https://cafebazaar.ir/app/ir.ebtekarai.app">Cafe Bazaar</a> and installable as a PWA</sub><br><sub dir="rtl">در کافه‌بازار و قابل نصب به‌صورت PWA</sub>

</td>
</tr>
</table>

### 📦 Repositories · مخزن‌ها

| | Repository | What's inside | محتوا |
|:-:|---|---|---|
| 📘 | **[ebtekar-ai](https://github.com/EbtekarAi/ebtekar-ai)** | Docs, developer guide, examples & [website](https://ebtekarai.github.io/ebtekar-ai/) | مستندات، راهنمای توسعه‌دهندگان و سایت |
| 🍳 | **[ebtekar-cookbook](https://github.com/EbtekarAi/ebtekar-cookbook)** | 10 recipes: streaming, tools, vision, JSON, retries … | ۱۰ دستور آماده: استریم، ابزارها، تصویر، JSON و… |
| 🧾 | **[openapi](https://github.com/EbtekarAi/openapi)** | OpenAPI 3.1 spec + Postman collection | مشخصات OpenAPI و مجموعهٔ Postman |
| 🚀 | **[getting-started](https://github.com/EbtekarAi/getting-started)** | Minimal backends: Node.js · FastAPI · PHP | کوچک‌ترین بک‌اند در سه زبان |
| 💬 | **[chat-ui](https://github.com/EbtekarAi/chat-ui)** | RTL web chat with a key-safe proxy (0 deps) | چت وب راست‌به‌چپ با پروکسی امن |
| ⌨️ | **[terminal-chatbot](https://github.com/EbtekarAi/terminal-chatbot)** | Chat with any model from your terminal | چت با هر مدل از داخل ترمینال |
| ✈️ | **[telegram-bot-starter](https://github.com/EbtekarAi/telegram-bot-starter)** | Your own AI bot on Telegram in 5 minutes | ربات هوش مصنوعی تلگرام در ۵ دقیقه |

### ⚡ Quick start · شروع سریع

```python
import os, anthropic

client = anthropic.Anthropic(
    api_key=os.environ["EBTEKAR_API_KEY"],                      # ebtekarai.ir/developers
    base_url="https://ebtekarai.ir/api/developer-gateway",
    default_headers={"User-Agent": "Ebtekar-Client/1.0"},
)
msg = client.messages.create(model="ebtekar-smart", max_tokens=512,
                             messages=[{"role": "user", "content": "سلام!"}])
print(msg.content[0].text)
```

<div align="center">

**Works with** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![cURL](https://img.shields.io/badge/cURL-073551?logo=curl&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?logo=anthropic&logoColor=white)

</div>

### 🤝 Community · ارتباط با ما

<div align="center">

[Telegram](https://t.me/EbtekarAi) · [Bale](https://ble.ir/EbtekarAi) · [Cafe Bazaar](https://cafebazaar.ir/app/ir.ebtekarai.app) · [ebtekarai.ir](https://ebtekarai.ir) · [Security policy](https://github.com/EbtekarAi/ebtekar-ai/blob/main/SECURITY.md)

<sub>Ideas, bugs or a new recipe? Open an issue in the matching repository. Contributions are welcome. 💜</sub><br>
<sub dir="rtl">ایده، باگ یا دستور تازه؟ در مخزن مربوط issue باز کنید؛ مشارکت شما خوشحالمان می‌کند.</sub>

</div>
