# 🌐 Virtual Browser Lite

A lightweight, web-based simulation of the Google Chrome browser interface. Built entirely with vanilla HTML, CSS, and JavaScript, this project provides a fully functional simulated browsing experience directly within your own web browser.

## ✨ Features

* **Tab Management:** Create, switch, and close multiple browser tabs seamlessly.
* **Web Navigation:** Fully functioning address bar with URL formatting, search engine integration, and standard controls (Back, Forward, Reload, Home).
* **Proxy-Based Browsing:** Uses a web proxy to render external sites inside iframes, bypassing basic CORS limitations.
* **Bookmarks System:** Star your favorite pages, access them instantly via the Bookmarks Bar, and easily **Export/Import** your bookmarks as JSON files.
* **History Tracking:** Logs your browsing history locally. View past pages or clear your history via the built-in History manager.
* **🤖 AI Copilot Side Panel:** Quick-access collapsible side panel featuring DuckDuckGo AI Chat.
* **Built-in Screenshot Tool:** Capture the current webpage or your entire screen using the integrated screen capture API and `html2canvas`.
* **Customization & Accessibility:** 
  * Auto-detecting and manually togglable **Dark/Light Mode**.
  * Viewport zoom controls (Zoom In/Out).
  * Full-Screen mode.
  * Customizable default search engines (Google, DuckDuckGo, Bing, Yahoo, Ecosia).
* **Persistent Storage:** Bookmarks, history, and settings are saved to your browser's `localStorage` so you don't lose them between sessions.
* **Responsive Design:** Adapts smoothly to mobile devices and smaller screen sizes.

## 🚀 How to Use

1. **Download the project:** Save the `index.html` file to your local machine.
2. **Run it:** Simply double-click the `index.html` file to open it in your preferred web browser. No server, build tools, or dependencies are required!

## ⚠️ Limitations & Notes

* **Iframe Restrictions:** Because this virtual browser uses `<iframe>` elements to display web pages, sites with strict `X-Frame-Options` or robust anti-framing security policies may refuse to connect or display properly, even with the proxy.
* **Data Privacy:** All data (history, bookmarks) is stored purely client-side via `localStorage`.

---
*Created for demonstration and educational purposes.*
