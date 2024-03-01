# ChatGPT All Search Engines

![License](https://img.shields.io/github/license/wong2/chatgpt-google-extension)

---

A browser extension to display ChatGPT response alongside Google (and other search engines) results. It is meant to support search engines and specifically SearX.

## Supported Search Engines

Google, Baidu, Bing, DuckDuckGo, Brave, Naver, Yandex, Kagi, SearX

Broken : Yahoo

Every SearX instance in searx.space is supported plus a bunch of other ones.
If you have a SearX instance that is not on searx.space, open an issue.

## Screenshot

![Screenshot](screenshots/extension.png?raw=true)

## Features

- Supports all popular search engines
- Supports the official OpenAI API
- Supports ChatGPT Plus
- Markdown rendering
- Code highlights
- Dark mode
- Provide feedback to improve ChatGPT
- Copy to clipboard
- Custom trigger mode
- Switch languages

## Troubleshooting

### How to make it work in Opera

![Screenshot](screenshots/opera.png?raw=true)

Enable "Allow access to search page results" in the extension management page

## Build from source

1. Clone the repo
2. Install dependencies with `npm install`
3. `npm run build`
4. Load `build/chromium/` or `build/firefox/` directory to your browser

## Credits
This extension is based on [chatgpt-google-extension](https://github.com/wong2/chatgpt-google-extension) by wong2

