# ⚡ Speed Check

> A lightweight, browser-based internet speed test by OpenUtility.

Speed Check is a fast and minimal web application for measuring key network performance metrics without a heavy frontend framework. It uses modern browser APIs and a responsive glassmorphic interface to visualize results in real time.

## ✨ Features

- 📥 **Download Speed** — Track download throughput in Mbps.
- 📤 **Upload Speed** — Measure upload throughput in Mbps.
- 📡 **Latency** — Measure network response time.
- 📊 **Live Gauge** — Visualize speed while the test is running.
- 🌐 **Streaming Measurements** — Uses the browser `ReadableStream` API for real-time data handling.
- 📱 **Responsive UI** — Designed for desktop and mobile screens.
- 🪶 **Lightweight** — Built with HTML, CSS, and vanilla JavaScript.
- 🎨 **OpenUtility Branding** — Modern dark UI with OpenUtility styling.

## 🧰 Technology

- HTML5
- CSS3
- Vanilla JavaScript (ES6+)
- `ReadableStream` API
- SVG graphics and animations
- Responsive CSS

No frontend framework is required.

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/OpenUtility2/Speed-Check.git
cd Speed-Check
```

Because the project is client-side and lightweight, it can be served with any static web server.

For example, with Python:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080` in your browser.

## 📈 What is measured?

| Metric | Description |
| --- | --- |
| **Latency** | Approximate network response time, normally shown in milliseconds. |
| **Download** | Approximate downstream throughput, shown in Mbps. |
| **Upload** | Approximate upstream throughput, shown in Mbps. |

Results can vary depending on your connection, server location, browser, device, network congestion, and other background traffic.

## 🔐 Privacy

Speed tests necessarily exchange network data with the service/test endpoint used by the application. Do not interpret the results as a security, privacy, or ISP diagnostic guarantee.

## 🧩 OpenUtility

Speed Check is one of the lightweight web utilities in the OpenUtility ecosystem, focused on useful browser-based tools with simple interfaces and minimal dependencies.

## 📄 License

See the repository for the applicable license.

Built with ❤️ by **OpenUtility**.
