# Telegram Tabanlı Yapay Zeka Asistanı 🤖📨

Bu proje, kullanıcıların Telegram üzerinden yazılı veya sesli komutlarla aşağıdaki işlemleri yapmasını sağlayan bir yapay zeka destekli asistandır:

- 📧 Gmail üzerinden e-posta gönderme, silme
- 📁 Google Drive dosya kopyalama/silme
- 📅 Google Takvim etkinlik ekleme ve listeleme
- 🎙️ Sesli mesajları metne çevirme (Whisper API)
- 🧠 Komutları yorumlama (ChatGPT - GPT-4o Mini)

## 🚀 Kullanılan Teknolojiler

- [n8n.io](https://n8n.io) (Workflow otomasyon platformu)
- OpenAI API (ChatGPT & Whisper)
- Google API (Gmail, Calendar, Drive)
- Telegram Bot API

## 🎥 Demo Videosu

🔗 [Tanıtım Videosu (Google Drive)](https://drive.google.com/file/d/1KWZT2HfGg8w0j66IpgDLPc8FOxevkGNp/view)

## 🛠 Kurulum

1. `project.json` dosyasını `n8n` içerisine import edin.
2. Telegram bot token’ınızı ve Google API bağlantılarını n8n'de yapılandırın.
3. Sistemi çalıştırın ve Telegram'dan test mesajları gönderin.

## 📎 Kaynaklar

- [OpenAI API Docs](https://platform.openai.com/docs)
- [Telegram Bot API](https://core.telegram.org/bots/api)
- [Google Workspace APIs](https://developers.google.com)
