# MIDILLI MIDI Web Tool & MIDI Monitor, Analyzer, and Sender

<img width="2372" height="1003" alt="image" src="https://github.com/user-attachments/assets/9db4506d-499c-4777-ae5c-43a4f09803a2" />

## 📌 Project Overview

**MIDILLI MIDI Web Tool** is a powerful web-based MIDI utility, serving as a Swiss Army knife for MIDI tasks. 
It allows real-time monitoring and sending of MIDI messages directly from your browser, no installation needed.

The project is based on a single library, **[midi.js](midi.js)**, which is a 1-to-1 reimplementation of  
[rtmidi](https://github.com/thestk/rtmidi) for the web, providing robust MIDI handling in the browser environment  
with a single HTML file.

**MIDI Monitor & Sender** is integrated into the tool, enabling seamless MIDI message inspection and transmission to 
connected MIDI devices.

Experience live demos and tools provided and maintained by MIDILLI Tech at [https://midilli.tech](https://midilli.tech).

## ⚙️ Features

- Real-time MIDI message monitoring: Note On/Off, Control Change (CC), Program Change, Pitch Bend, SysEx, and more.
- Send customized MIDI messages to selected MIDI output device.
- Visual Piano Roll displaying incoming MIDI notes.
- CC Analyzer with color-coded bar graphs for selected CC numbers.
- Message filtering by MIDI channel and message type.
- Export MIDI data logs.
- Works on modern browsers supporting Web MIDI API (Chrome, Edge, Firefox experimental).

## Screenshots

<img width="1032" height="650" alt="image" src="https://github.com/user-attachments/assets/ef43a169-9c61-448a-bf55-0f97df91ff02" />CC Analyzer

Some more info on these pages: 
- [MIDI Monitor is Now MIDI Monitor and Sender ](https://midilli.tech/midi-monitor-is-now-midi-monitor-and-sender/)
- [MIDILLI MIDI Web Tool: The New Swiss Army Knife for MIDI ](https://midilli.tech/midilli-midi-web-tool-the-new-swiss-army-knife-for-midi)

## 🚀 Getting Started

**To use the MIDILLI MIDI Web Tool:**

1. Make sure your browser supports and allows MIDI access.  
   Check support here: [https://caniuse.com/midi](https://caniuse.com/midi)

2. Open the live web tool at:  
   [https://midilli.tech/midi-web-tool](https://midilli.tech/midi-web-tool)

3. When prompted, allow MIDI access in your browser.

4. Select one or multiple devices from the list and click **Connect**.

**Browser support summary:**

| Browser          | Version Supported | Notes                 |
|------------------|-------------------|-----------------------|
| Google Chrome    | 43+               | Full support          |
| Microsoft Edge   | 79+               | Full support          |
| Firefox          | 108+              | Experimental support  |
| Opera            | 30+               | Full support          |
| Safari           | —                 | Not supported         |
| Safari on iOS    | —                 | Not supported         |

> **Note:** Safari and Safari iOS do not currently support the Web MIDI API.  
> Source: [caniuse.com/midi](https://caniuse.com/midi)


## 🤝 Contribution

Contributions, bug reports, and feature requests are welcome!

1. Fork the repository.
2. Make your changes.
3. Submit a pull request for review.

Please adhere to coding guidelines and write clear commit messages.

## 📄 License

This project is licensed under the **Apache License 2.0**. See the [LICENSE](LICENSE) file for details.

---

Powered by MIDILLI Tech — bringing flexibility and power to your MIDI workflow.
