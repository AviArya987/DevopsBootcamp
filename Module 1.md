<div align="center">

<!-- Inline dark banner SVG -->
<svg width="100%" height="220" viewBox="0 0 1200 220" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Zero to Cloud Ready Banner">
  <defs>
    <linearGradient id="g1" x1="0" x2="1">
      <stop offset="0" stop-color="#0f1720"/>
      <stop offset="1" stop-color="#0b1220"/>
    </linearGradient>
  </defs>
  <rect width="1200" height="220" fill="url(#g1)"/>
  <!-- Cloud icon -->
  <g transform="translate(48,48) scale(1.2)">
    <path d="M60 10c-18 0-33 14-33 31 0 2 0 4 1 6-11 1-20 10-20 22 0 12 9 22 20 22h76c18 0 33-14 33-31 0-16-14-29-31-31-4-17-19-29-39-29z" fill="#6EE7B7"/>
    <path d="M92 66c-8 0-14-6-14-14s6-14 14-14 14 6 14 14-6 14-14 14z" fill="#FFFFFF"/>
  </g>

  <!-- Title -->
  <text x="220" y="95" font-family="Inter, Arial" font-size="36" fill="#E6EEF3" font-weight="700">ZERO TO</text>
  <text x="220" y="150" font-family="Inter, Arial" font-size="64" fill="#FFB86B" font-weight="800">CLOUD READY</text>

  <!-- Subtitle -->
  <text x="220" y="183" font-family="Inter, Arial" font-size="14" fill="#9FB3C8">Module 1 — Computer Basics • Playful • Visual • Beginner-first</text>

  <!-- Badges (visual) -->
  <g transform="translate(820,32)">
    <rect x="0" y="0" rx="8" ry="8" width="240" height="36" fill="#0f1720" stroke="#22303c"/>
    <text x="14" y="24" font-family="Inter" font-size="14" fill="#9EE7C8">🟢 Level: Beginner</text>
  </g>
</svg>

</div>

<p align="center">
  <img src="https://img.shields.io/badge/Module-1-8A2BE2?style=for-the-badge&logo=book" alt="module"/>
  <img src="https://img.shields.io/badge/Length-4%20Hours-00BFFF?style=for-the-badge" alt="length"/>
  <img src="https://img.shields.io/badge/Style-Playful-orange?style=for-the-badge" alt="style"/>
</p>

---

# 🖥️ Module 1 — Computer Basics (Playful • Visual • Hands-on)

**Overview**  
This module is a fun, visual, and practical intro that builds *how a computer operates* (not just "what it is"), basic number systems, OS fundamentals, and the internet flow — all in beginner language with micro-exercises and visuals.

---

## 📚 Quick links
- [1 — How a Computer Operates](#1-how-a-computer-operates)  
- [2 — OS Fundamentals](#2-os-fundamentals)  
- [3 — Internet Basics](#3-internet-basics)  
- [4 — Exercises & Summary](#4-exercises--summary)

---

## 1 — How a Computer Operates

**Goal:** Understand the *operation* loop, CPU fetch-decode-execute, RAM vs Storage, and binary basics.

### 1.1 Operation Loop
**Explain:** Input → Process → Output → Storage

**Visual (SVG inline):**
<svg viewBox="0 0 700 120" width="100%" height="120" xmlns="http://www.w3.org/2000/svg">
  <defs><linearGradient id="lg" x1="0" x2="1"><stop offset="0" stop-color="#071428"/><stop offset="1" stop-color="#0b1b2b"/></linearGradient></defs>
  <rect width="700" height="120" fill="transparent"/>
  <!-- Boxes -->
  <g font-family="Inter, Arial" font-size="14">
    <rect x="20" y="30" rx="8" ry="8" width="140" height="60" fill="#081826" stroke="#1b3b4a"/>
    <text x="90" y="62" fill="#A7E3D7" text-anchor="middle">Input</text>
    <rect x="190" y="30" rx="8" ry="8" width="140" height="60" fill="#081826" stroke="#1b3b4a"/>
    <text x="260" y="62" fill="#FFD8A8" text-anchor="middle">CPU (Process)</text>
    <rect x="360" y="30" rx="8" ry="8" width="140" height="60" fill="#081826" stroke="#1b3b4a"/>
    <text x="430" y="62" fill="#A7E3D7" text-anchor="middle">Output</text>
    <rect x="530" y="30" rx="8" ry="8" width="140" height="60" fill="#081826" stroke="#1b3b4a"/>
    <text x="600" y="62" fill="#F0B3A2" text-anchor="middle">Storage</text>
    <!-- Arrows -->
    <path d="M160 60 H190" stroke="#4ecdc4" stroke-width="2" marker-end="url(#arr)"/>
    <path d="M330 60 H360" stroke="#ffd86b" stroke-width="2"/>
    <path d="M500 60 H530" stroke="#ff9bb3" stroke-width="2"/>
    <!-- Back arrow to storage -->
    <path d="M470 95 Q430 115 390 95" fill="transparent" stroke="#7bd389" stroke-width="2"/>
  </g>
  <defs>
    <marker id="arr" markerWidth="6" markerHeight="6" refX="6" refY="3" orient="auto">
      <path d="M0 0 L6 3 L0 6 z" fill="#4ecdc4"/>
    </marker>
  </defs>
</svg>


---

### 1.2 CPU: Fetch → Decode → Execute
**Explain briefly:**  
- **Fetch:** CPU reads instruction from memory  
- **Decode:** CPU figures out what to do  
- **Execute:** CPU performs the operation

**Analogy:** Chef (CPU) reads recipe (instruction), decodes the step, executes it.

**Tiny example:**  
Pseudo-instruction: `ADD R1, R2 -> R3`  
- Fetch `ADD` instruction  
- Decode (it's addition)  
- Execute (take registers R1+R2 put into R3)

---

### 1.3 RAM vs Storage
**Explain:**  
- RAM = temporary working area, very fast, cleared on shutdown  
- Storage = SSD/HDD, persistent, slower

**Visual (ASCII):**
```

+--------------------+   +--------------------+
|   RAM (working)    |   |   Storage (disk)   |
|  - running apps     |   | - files & OS image |
+--------------------+   +--------------------+

```

**Mini task:** Open two apps — close one — watch memory usage (Task Manager / Activity Monitor).

---

### 1.4 Bits, Bytes & Number Systems
**Explain:** Bit (0/1), Byte=8 bits, Binary & Hex quick conversions.

**Mini activity:** Convert decimal 13 → binary  
(Answer: `1101`)

**Cheat sheet:**
- `0xFF` = `255` decimal
- `1 KB` = `1024 bytes`

---

## 2 — OS Fundamentals

**Goal:** Know what an OS does, kernel role, processes vs threads, and program lifecycle.

### 2.1 What an OS Does
**Explain:** Resource manager, user interface, security layer, file manager, scheduler.

**Fun line:** OS is the “party host” that keeps guests (apps) from fighting over chairs (CPU/RAM).

---

### 2.2 Kernel
**Explain:** Core component that interacts with hardware, isolates processes, and provides drivers.

**Quick visual:**
```

[Apps GUI/CLI]
↓
[Operating System (User Space)]
↓
[Kernel (Core, drivers, scheduler)]
↓
[Hardware]

```

**Micro-check:** Why shouldn't user apps access hardware directly? (Security, stability)

---

### 2.3 Processes vs Threads
**Explain:**  
- Process = sandboxed program with its own memory  
- Thread = execution path within process, shares memory

**Visual (SVG simplified):**
<svg width="100%" height="120" viewBox="0 0 600 120" xmlns="http://www.w3.org/2000/svg">
  <rect x="10" y="10" width="580" height="100" rx="8" fill="#071428" stroke="#1b3b4a"/>
  <text x="40" y="40" fill="#A7E3D7" font-family="Inter" font-size="13">Process: MyApp</text>
  <rect x="40" y="50" width="140" height="40" rx="6" fill="#0e2430" stroke="#1b3b4a"/>
  <text x="110" y="76" fill="#FFD8A8" font-family="Inter" font-size="12" text-anchor="middle">Thread A (UI)</text>
  <rect x="220" y="50" width="140" height="40" rx="6" fill="#0e2430" stroke="#1b3b4a"/>
  <text x="290" y="76" fill="#FFD8A8" font-family="Inter" font-size="12" text-anchor="middle">Thread B (Network)</text>
  <rect x="400" y="50" width="140" height="40" rx="6" fill="#0e2430" stroke="#1b3b4a"/>
  <text x="470" y="76" fill="#FFD8A8" font-family="Inter" font-size="12" text-anchor="middle">Thread C (Render)</text>
</svg>

**Exercise:** Name two apps on your device and imagine what threads they might have.

---

### 2.4 How Programs Run
**Explain flow:** Source → (compile/interpret) → machine code → CPU → output.

**Example:** Python code is interpreted (line by line). C code is compiled into machine code.

---

## 3 — Internet Basics

**Goal:** Understand DNS, HTTP vs HTTPS, client-server lifecycle, and what happens on a page load.

### 3.1 URL → Page
**Step flow:**  
1. Browser cache check  
2. DNS resolution (domain → IP)  
3. TCP/TLS handshake  
4. HTTP(S) request/response  
5. Browser rendering (HTML/CSS/JS)

**SVG mini-flow:**
<svg viewBox="0 0 700 120" width="100%" height="120" xmlns="http://www.w3.org/2000/svg">
  <rect width="700" height="120" fill="transparent"/>
  <text x="20" y="28" font-family="Inter" fill="#A7E3D7">You</text>
  <text x="110" y="28" font-family="Inter" fill="#FFD8A8">Browser</text>
  <text x="280" y="28" font-family="Inter" fill="#9EE7C8">DNS</text>
  <text x="450" y="28" font-family="Inter" fill="#FFB86B">Server</text>
  <path d="M40 40 H100" stroke="#7bd389" stroke-width="2" marker-end="url(#arrow)"/>
  <path d="M140 40 H260" stroke="#4ecdc4" stroke-width="2" marker-end="url(#arrow)"/>
  <path d="M320 40 H430" stroke="#ffd86b" stroke-width="2" marker-end="url(#arrow)"/>
  <defs>
    <marker id="arrow" markerWidth="6" markerHeight="6" refX="6" refY="3" orient="auto">
      <path d="M0 0 L6 3 L0 6 z" fill="#4ecdc4"/>
    </marker>
  </defs>
</svg>

---

### 3.2 DNS — the phonebook
**Explain:** DNS maps human names to IP addresses. It is hierarchical (root → TLD → authoritative).

**Quick task:** `nslookup example.com` (or use online DNS lookup).

---

### 3.3 HTTP vs HTTPS
**Table:**

| HTTP | HTTPS |
|------|--------|
| No encryption | TLS encryption |
| Port 80 | Port 443 |
| Use for public static content (legacy) | Required for logins/payments |

**Analogy:** HTTP = postcard, HTTPS = sealed letter.

---

### 3.4 Client–Server Model
**Explain:** Client requests, Server responds. Stateless nature of HTTP; cookies/ sessions for state.

**Example scenarios:** Logging in to a site, fetching an image, streaming video.

---

## 4 — Exercises & Summary

### Quick Exercises
1. Convert decimal **21** → binary.  
2. Explain in one sentence: Why does RAM matter?  
3. Use `ping` or open DevTools → Network tab and refresh any site. What files load first?  
4. Draw the flow of a browser request (on paper).

### Recap
- CPU = executor (fetch/decode/execute)  
- RAM = working area; Storage = long-term  
- OS (kernel) manages resources and isolation  
- DNS resolves names; HTTPS secures traffic

### Next steps (5 min)
- Module 2 — **Linux Fundamentals** (terminal, commands, file system)  
- Module 3 — **Networking** (IP, routing, ports)  
- Module 4 — **Git & GitHub** and so on...
---

<p align="center">
  <sub style="color:#8da7b1">Made with ❤️ — Zero to Cloud Ready • Module 1</sub>
</p>
```

---

If you want any tweak (different banner colors, swap icons, more/less emoji, or a one-page printable PDF), tell me which part & I’ll update the `README.md` immediately.
