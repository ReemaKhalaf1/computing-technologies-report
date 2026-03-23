# Computing Technologies Report 💻🌐📡

## 📌 Overview
This report was developed as part of the **CI405 Computing Technologies** module at the University of Brighton. It explores three core areas:
- **Hardware Components** — CPU, memory, storage, and the abstraction-performance trade-off.
- **Data Communication** — OSI model, TCP/IP, network latency analysis, and protocol evolution (HTTP/3, QUIC).
- **Internet of Things (IoT)** — Resource-constrained systems, RTOS vs. general-purpose OS, and simulation of a smart agriculture pipeline.

## 🛠️ Key Technical Work
- **System call tracing** to measure kernel-space overhead.
- **Network path analysis** using `mtr`, `ping`, and `traceroute`.
- **Protocol benchmarking**: HTTP/1.1 vs HTTP/2 vs HTTP/3 (QUIC) — latency reduced by 67%.
- **IoT simulation** in bash and Python with performance benchmarking (memory, CPU, response time).
- **RTOS comparison**: FreeRTOS vs Linux on resource-constrained hardware.

## 📊 Key Findings
| Metric | Linux (Minimal) | FreeRTOS |
|--------|-----------------|---------|
| Boot Time | 1.5–3 s | < 50 ms |
| Idle Power | ~85 mA | ~12 μA |
| Memory Footprint | 8–16 MB | 128–512 KB |
| Context Switch | 15–20 μs | < 2 μs |

## 📁 Files
| File | Description |
|------|-------------|
| `CT_ATT1.pdf` | Full report (3500 words) with practical simulations and references |

## 👩‍💻 Author
**Reema Khalaf**  
BSc (Hons) Computer Science with Cybersecurity | University of Brighton  
📍 Brighton, UK  
🔗 [LinkedIn](https://www.linkedin.com/in/reema-khalaf) | [GitHub](https://github.com/ReemaKhalaf1)
