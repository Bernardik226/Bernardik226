**Computer Engineer · embedded systems and backend**

C/C++ firmware for Espressif MCUs (ESP32, ESP32-S3), Python/FastAPI servers and the glue between them, with automated tests and CI.

### Projects

**[Tinto](https://github.com/Bernardik226/Tinto)** · pocket planner with an e-ink display. Hold the button, speak, and it becomes a Google Calendar event.
- C firmware on the ESP32-S3 (ESP-IDF 5.3), plus a simulator that runs the UI on a PC, no board needed
- FastAPI server: Whisper transcription, parsing with the Claude API, Google Calendar and Tasks integration
- Setup PWA
- 724 firmware tests, 282 server tests, GitHub Actions
- Firmware compiled to WebAssembly, runs in the browser: **[demo](https://bernardik226.github.io/Tinto/)**

**[espnokia-phone](https://github.com/Bernardik226/espnokia-phone)** · a Nokia 3310 that talks to Claude.
- C++17 firmware on the ESP32 (PlatformIO), apps and games on an 84×48 screen
- Case modeled and 3D printed
- FastAPI server with voice (Whisper) and Claude, in Docker, with a web dashboard
- 120 native tests, 182 server tests, GitHub Actions

<img src="https://skillicons.dev/icons?i=c,cpp,python,fastapi,js,docker,githubactions,linux,git" alt="C, C++, Python, FastAPI, JavaScript, Docker, GitHub Actions, Linux, Git" />
