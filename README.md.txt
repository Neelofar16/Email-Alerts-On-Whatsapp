# Gmail to WhatsApp Alert System 📩➡📱

This Python script automatically checks your Gmail inbox for new/unread emails and instantly sends alerts via WhatsApp using `pywhatkit`.

## 🔧 Features

- Gmail authentication and email fetching using IMAP.
- WhatsApp notifications using `pywhatkit`.
- Runs in the background and checks every 1 minute.

## 🔐 Setup

1. **Enable IMAP in Gmail Settings.**
2. **Allow Less Secure Apps** (or use an App Password).
3. Replace your credentials in `main.py`.

## 🔁 Usage

```bash
python main.py
