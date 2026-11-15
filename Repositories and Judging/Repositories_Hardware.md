## Hardware Repositories (13 repos)

| Difficulty | Repository | Stack | Setup notes | AI policy |
| --- | --- | --- | --- | --- |
| Easy | [CircuitVerse](https://github.com/CircuitVerse/CircuitVerse) | Ruby on Rails + JS | Dockerfile and docker-compose provided; Rails + Node dependencies | Allowed with disclosure. PR template asks you to declare AI use, confirm you reviewed every line, and explain the approach in your own words |
| Easy | [tscircuit](https://github.com/tscircuit/tscircuit) | TypeScript (Bun) | bun install / bun test, no Docker. Umbrella repo; core logic lives in separate @tscircuit packages | None found. README encourages AI coding tools |
| Easy | [OpenCircuits](https://github.com/OpenCircuits/OpenCircuits) | TypeScript/Node monorepo + backend | Dockerfile + package.json; frontend and backend set up separately | None found |
| Easy | [WireViz](https://github.com/wireviz/WireViz) | Python | pip install; Graphviz must be installed | None found |
| Easy | [Logisim-evolution](https://github.com/logisim-evolution/logisim-evolution) | Java | Needs Java 21+; Gradle build; no devcontainer | None found |
| Medium | [ArduinoCore-avr](https://github.com/arduino/ArduinoCore-avr) | C/C++ (Arduino core) | No build system of its own; test via Arduino IDE or arduino-cli, ideally with a board | None found; no CONTRIBUTING file |
| Medium | [Ripes](https://github.com/mortbopet/Ripes) | C++ / Qt 6 | CMake + Qt 6; WASM web build also exists | None found |
| Medium | [cocotb](https://github.com/cocotb/cocotb) | Python (+ HDL simulator) | pip/pytest; needs a simulator such as Icarus, GHDL or Verilator | None found |
| Medium | [WLED](https://github.com/wled/WLED) | C++ firmware (ESP32/ESP8266) + web UI | PlatformIO in VS Code (Arduino IDE no longer supported); Node for the web UI | Allowed, but you are responsible for the code. Purely vibe-coded PRs will be rejected. CodeRabbit AI reviews PRs |
| Medium | [PCB Cupid](https://github.com/qninth/awesome-digital-ic) | Curated link list (Markdown) | Nothing to build; contributions are PRs adding links | None found |
| Hard | [CVA6](https://github.com/openhwfoundation/cva6) | SystemVerilog | Needs RISC-V GCC toolchain (build via provided scripts) plus a Verilator model | Heavy AI-assisted code OK if the human reviews and understands it. Automated or LLM-generated PRs are closed without review; discussion replies must be your own |
| Hard | [Verible](https://github.com/chipsalliance/verible) | C++ | Bazel build; slow first build | None found |
| Hard | [Eclipse ThreadX](https://github.com/eclipse-threadx/threadx) | C | CMake + Ninja, GCC 14 on Linux (scripts/install.sh on Ubuntu); Eclipse Contributor Agreement required | Welcome with attribution. Mark AI-assisted files, name the tool and model in the commit; the human is responsible |
