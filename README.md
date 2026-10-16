<!-- ═══════════════════════════  HEADER  ═══════════════════════════ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:1565C0,75:6A1B9A,100:E65100&height=230&section=header&text=Siddhant%20Singh&fontSize=64&fontColor=ffffff&fontAlignY=36&desc=I%20build%20systems%20from%20the%20transistor%20to%20the%20cloud&descSize=19&descAlignY=58&animation=fadeIn" alt="Siddhant Singh" width="100%"/>
</p>

<p align="center">
  <a href="https://github.com/siddhaantxsingh">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=2600&pause=700&color=58A6FF&center=true&vCenter=true&width=760&lines=Distributed+systems+%E2%80%A2+Raft+%E2%80%A2+LSM+trees+%E2%80%A2+CRDT%2FOT;LLM+inference+engines+in+Rust+%E2%80%A2+CUDA+tensor-core+kernels;RISC-V+cores+%E2%80%A2+systolic+arrays+%E2%80%A2+UVM+%E2%80%A2+sky130+GDSII;If+it+isn't+tested%2C+it+isn't+done.;23+repos.+Every+claim+has+a+test+behind+it." alt="What I build"/>
  </a>
</p>

<!-- ═══════════════════════════  PROFILES (all clickable)  ═══════════════════════════ -->
<p align="center">
  <a href="https://www.linkedin.com/in/LINKEDIN_SLUG/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://leetcode.com/u/LEETCODE_USERNAME/"><img src="https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
  <a href="https://codeforces.com/profile/CODEFORCES_HANDLE"><img src="https://img.shields.io/badge/Codeforces-Profile-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces"/></a>
  <a href="https://www.codechef.com/users/CODECHEF_HANDLE"><img src="https://img.shields.io/badge/CodeChef-Profile-5B4638?style=for-the-badge&logo=codechef&logoColor=white" alt="CodeChef"/></a>
  <a href="HDLBITS_URL"><img src="https://img.shields.io/badge/HDLBits-Verilog-8A2BE2?style=for-the-badge&logo=v&logoColor=white" alt="HDLBits"/></a>
  <a href="mailto:siddhaantxsingh@gmail.com"><img src="https://img.shields.io/badge/Email-Say_hi-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="RESUME_URL"><img src="https://img.shields.io/badge/Résumé-PDF-2E7D32?style=for-the-badge&logo=readdotcv&logoColor=white" alt="Résumé"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=siddhaantxsingh&label=Profile%20views&color=6A1B9A&style=flat-square" alt="Profile views"/>
  <img src="https://img.shields.io/github/followers/siddhaantxsingh?label=Followers&style=flat-square&color=1565C0&logo=github" alt="Followers"/>
  <img src="https://img.shields.io/badge/Open_to-SDE_%2F_VLSI_%2F_ML--infra_roles-2E7D32?style=flat-square" alt="Open to roles"/>
</p>

---

<!-- ═══════════════════════════  ABOUT — written as hardware  ═══════════════════════════ -->

<table>
<tr>
<td width="55%" valign="top">

### ⚡ `$ whoami`

```systemverilog
module siddhant_singh #(
  parameter string  SCHOOL  = "MIT Manipal",
  parameter string  DEGREE  = "B.Tech ECE — VLSI Design & Technology",
  parameter string  HOME    = "Jamshedpur, India",
  parameter int     GRAD    = 2028
)(
  input  logic        clk,           // coffee
  input  logic [7:0]  hard_problem,
  output logic [63:0] shipped_system
);
  // software engineer who can also read a timing report
  always_ff @(posedge clk) begin
    if (hard_problem != '0)
      shipped_system <= measure(fix(break_on_purpose(
                          build(hard_problem))));
  end

  // SVA: I don't claim what I haven't measured
  assert property (@(posedge clk)
    claim |-> ##[0:$] evidence);
endmodule
```

</td>
<td width="45%" valign="top">

### 🧭 Right now

- 🎓 **B.Tech ECE (VLSI)** at **MIT Manipal**
- 🏭 **ML Intern @ Tata Steel** (Jun–Jul 2026)
- 🧪 **Published research paper** → [read it](PAPER_URL)
- 🏁 **Arm Bharat AI-SoC Challenge 2026–27** — team entry
- 🔨 **23 tested systems** across SWE, AI infra and silicon
- 🎯 Looking for **SDE / VLSI / ML-infra** internships & new-grad roles (2027)

### 💬 Ask me about

Raft · LSM trees · CRDTs · paged KV caches · tensor cores · ZeRO · systolic arrays · UVM · timestamp reconstruction for sensor streams

</td>
</tr>
</table>

---

<!-- ═══════════════════════════  HOW IT ALL CONNECTS  ═══════════════════════════ -->

## 🗺️ One engineer, the whole stack

> From a MOSFET simulated in Sentaurus, to a RISC-V core in GDSII, to CUDA kernels, to an LLM serving engine, to the cloud control plane that schedules it — every layer built and tested.

```mermaid
flowchart TB
    subgraph SI["🔬 Silicon & RTL"]
        direction LR
        INV["CMOS inverter"]:::si
        MM["Matrix multipliers"]:::si
        RV["RISC-V CPU"]:::si
        ACC["INT8/FP8 accelerator"]:::si
        UVM["UVM verification"]:::si
    end
    subgraph AC["⚡ Accelerated compute"]
        direction LR
        CUDA["CUDA tensor-core kernels"]:::ac
        DT["Distributed training"]:::ac
        LLM["LLM inference engine"]:::ac
    end
    subgraph SY["🗄️ Systems & storage"]
        direction LR
        RAFT["Raft KV store"]:::sy
        LSM["LSM engine"]:::sy
        VDB["Vector DB"]:::sy
        EMB["EMBER compiler"]:::sy
        TAN["TANDEM editor"]:::sy
    end
    subgraph PL["☁️ Platforms & products"]
        direction LR
        NEB["Nebula GPU cloud"]:::pl
        INX["InferX"]:::pl
        EVA["EvalOps"]:::pl
        GW["Groundwork"]:::pl
        CAM["Campus AI OS"]:::pl
        MCP["MCP Fabric"]:::pl
        VC["VerifyCloud"]:::pl
    end
    subgraph ED["📡 Edge & devices"]
        direction LR
        MESP["MESP wearable"]:::ed
        IE["Industrial edge"]:::ed
        EF["EdgeFleet OTA"]:::ed
    end

    INV ~~~ MM ~~~ RV ~~~ ACC ~~~ UVM
    CUDA ~~~ DT ~~~ LLM
    RAFT ~~~ LSM ~~~ VDB ~~~ EMB ~~~ TAN
    NEB ~~~ INX ~~~ EVA ~~~ GW ~~~ CAM ~~~ MCP ~~~ VC
    MESP ~~~ IE ~~~ EF
    PL ~~~ SY ~~~ ED ~~~ AC ~~~ SI

    classDef si fill:#6A1B9A,stroke:#4A148C,color:#fff
    classDef ac fill:#76B900,stroke:#4E7A00,color:#000
    classDef sy fill:#1565C0,stroke:#0D47A1,color:#fff
    classDef pl fill:#E65100,stroke:#BF360C,color:#fff
    classDef ed fill:#00838F,stroke:#006064,color:#fff
    style SI fill:transparent,stroke:#6A1B9A,stroke-dasharray:5 5
    style AC fill:transparent,stroke:#76B900,stroke-dasharray:5 5
    style SY fill:transparent,stroke:#1565C0,stroke-dasharray:5 5
    style PL fill:transparent,stroke:#E65100,stroke-dasharray:5 5
    style ED fill:transparent,stroke:#00838F,stroke-dasharray:5 5
```

---

<!-- ═══════════════════════════  PROOF WALL  ═══════════════════════════ -->

## 🏆 The proof wall

<p align="center"><i>Not "built a X". Here's what each one <b>survived</b>.</i></p>

### 🗄️ Distributed systems & storage

| Project | What it is | Proof |
|---|---|---|
| 🗳️ **[RAFT-KV](https://github.com/siddhaantxsingh/RAFT-KV)** | Linearizable distributed KV store in Go, zero dependencies | Chaos runs all linearizable · 5-node failover ≤ **757 ms** |
| 🌲 **[LSM_ENGINE](https://github.com/siddhaantxsingh/LSM_ENGINE)** | LSM-tree storage engine in Rust | **6,055** power-loss crash images verified · **9,247** bit flips, 0 silent |
| 🧭 **[VECTORDB](https://github.com/siddhaantxsingh/VECTORDB)** | Persistent HNSW + PQ vector search in Rust | recall@10 **0.9999** · ≥ FAISS · **15.4×** compression |
| 🔥 **[EMBER](https://github.com/siddhaantxsingh/EMBER-Compiler)** | Typed language → optimizing compiler → GC'd VM → LLVM JIT (C++20) | **20,000** differential programs, 0 failures · fuzzed, ASan/UBSan clean |
| ✍️ **[TANDEM](https://github.com/siddhaantxsingh/TANDEM-Collaborative-Editor)** | Real-time collaborative code editor | `kill -9` mid-write: **3,706 acks, 0 lost** |

### ⚡ AI infrastructure

| Project | What it is | Proof |
|---|---|---|
| 🦀 **[LLM-INFERENCE-ENGINE](https://github.com/siddhaantxsingh/LLM-INFERENCE-ENGINE)** | vLLM-style server from scratch in Rust: paged KV, continuous batching, speculative decoding | Perplexity **18.8685** vs llama.cpp 18.8695 · **3.1×** batching throughput |
| 🟩 **[CUDA-KERNELS](https://github.com/siddhaantxsingh/CUDA-KERNELS)** | Naive → tensor-core kernels + a CPU SIMT emulator | `HMMA.16816.F32` in SASS · **170/170** checks · 0 spills on sm_80/89/90 |
| 🌐 **[DISTRIBUTED-TRAINING](https://github.com/siddhaantxsingh/DISTRIBUTED-TRAINING)** | DDP + ZeRO-1 + ring all-reduce from first principles | Matches PyTorch DDP to **1.6e-15** · crash-resume **bit-identical** |
| 🚦 **[INFERX](https://github.com/siddhaantxsingh/INFERX)** | KV-cache-aware LLM gateway + autoscaler | **1.68×** req/s · cache hits **48% → 66%** |
| ☁️ **[NEBULA](https://github.com/siddhaantxsingh/NEBULA_GPU_CLOUD)** | Multi-tenant GPU cluster control plane in Rust | EASY backfill **3.5×** lower wait · journal crash-tested at every byte |
| 📏 **[EVALOPS](https://github.com/siddhaantxsingh/EVALOPS)** | CI for LLMs with a significance-aware regression gate | False-positive rate **2–9%** at α = 0.05 · power **> 90%** |
| 📚 **[GROUNDWORK](https://github.com/siddhaantxsingh/GROUNDWORK)** | RAG engine where every sentence cites and is checked | NDCG@10 **0.470 → 0.550** · 5.8 ms answers |
| 🔐 **[MCP-FABRIC](https://github.com/siddhaantxsingh/MCP-FABRIC)** | Secure federating gateway for Model Context Protocol | alg=none / key-confusion JWT attacks rejected · **~2.3 ms** overhead |
| 🎓 **[CAMPUS-AI-OS](https://github.com/siddhaantxsingh/CAMPUS-AI-OS)** | Multi-tenant course Q&A with k-anonymous analytics | **10/10** audit defects fixed · 100% cited answers |

### 🔬 Silicon, RTL & verification

| Project | What it is | Proof |
|---|---|---|
| 🧠 **[RISCV-CPU](https://github.com/siddhaantxsingh/RISCV-CPU)** | RISC-V core with caches, taken through sky130 | **64/64** riscv-tests · **400/400** identical to Spike · ~96k random IRQs precise |
| 🔢 **[INT8-FP8 accelerator](https://github.com/siddhaantxsingh/INT8-FP8-ACCELARATOR)** | N×N systolic array with exact FP8 accumulation | Bit-exact vs golden model · PE routed to **GDSII @ 100 MHz** |
| ✅ **[UVM-SOC-VERIFICATION](https://github.com/siddhaantxsingh/UVM-SOC-VERIFICATION)** | UVM environment for an APB subsystem | **23** SVA properties · RAL · tested with the bugs it must catch |
| 🏭 **[VerifyCloud](https://github.com/siddhaantxsingh/VerifyCloud)** | CI for hardware: sandboxed RTL regression farm | **0** duplicate claims in 8,080 · **6/6** adversarial RTL contained |
| ⚖️ **[Matrix multipliers](https://github.com/siddhaantxsingh/Comparative-Analysis-Of-Different-Kind-of-Matrix-Multipliers-Using-Verilog)** | Serial vs parallel vs pipelined in a 90 nm Cadence flow | **9/9** designs meet 250 MHz · parallel = **82×** serial throughput |
| 🔌 **[CMOS inverter](https://github.com/siddhaantxsingh/MIXED-NODE-CMOS-INVERTER)** | Mixed-mode inverter in Sentaurus + my own DEVSIM model | t<sub>p</sub> **33.3 ps** @ 10 fF · peak gain **18.6** |

### 📡 Edge, IoT & devices

| Project | What it is | Proof |
|---|---|---|
| 🫀 **[MESP platform](https://github.com/siddhaantxsingh/Mesp_platform)** | STM32 + BLE wearable → real-time ECG/PPG/IMU console | **~6,400** frames/s · firmware golden vectors byte-exact · **122** tests |
| 🏭 **[INDUSTRIAL_EDGE](https://github.com/siddhaantxsingh/INDUSTRIAL_EDGE)** | Modbus → edge analytics → INT8 model → MQTT/TLS, in Go | `kill -9` + broker outage: **0 records lost** · 11 KB INT8 model |
| 🛰️ **[EDGEFLEET](https://github.com/siddhaantxsingh/EDGEFLEET)** | Signed OTA with canary waves and A/B rollback | Bad release reached **15 of 2,000** devices — all self-healed |

---

<!-- ═══════════════════════════  TECH STACK  ═══════════════════════════ -->

## 🧰 Toolbox

<p align="center"><b>Languages</b><br/>
  <img src="https://skillicons.dev/icons?i=cpp,c,rust,go,py,ts,js,bash&perline=8" alt="Languages"/>
</p>
<p align="center"><b>Hardware</b><br/>
  <img src="https://img.shields.io/badge/SystemVerilog-8A2BE2?style=for-the-badge" alt="SystemVerilog"/>
  <img src="https://img.shields.io/badge/Verilog-6A1B9A?style=for-the-badge" alt="Verilog"/>
  <img src="https://img.shields.io/badge/UVM_·_SVA-4A148C?style=for-the-badge" alt="UVM"/>
  <img src="https://img.shields.io/badge/CUDA_·_PTX-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA"/>
  <img src="https://img.shields.io/badge/Cadence_Genus_·_Innovus-D71920?style=for-the-badge" alt="Cadence"/>
  <img src="https://img.shields.io/badge/Synopsys_Sentaurus-5A2D82?style=for-the-badge" alt="Sentaurus"/>
  <img src="https://img.shields.io/badge/OpenLane_·_sky130-0F766E?style=for-the-badge" alt="OpenLane"/>
  <img src="https://img.shields.io/badge/STM32_·_nRF52-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white" alt="STM32"/>
</p>
<p align="center"><b>Systems, AI & cloud</b><br/>
  <img src="https://skillicons.dev/icons?i=linux,docker,kubernetes,postgres,redis,pytorch,react,fastapi,nodejs,git,githubactions,llvm&perline=12" alt="Systems and cloud"/>
</p>

---

<!-- ═══════════════════════════  COMPETITIVE PROGRAMMING  ═══════════════════════════ -->

## ⚔️ Competitive programming

<p align="center">
  <a href="https://leetcode.com/u/LEETCODE_USERNAME/">
    <img src="https://leetcard.jacoblin.cool/LEETCODE_USERNAME?theme=dark&font=JetBrains%20Mono&ext=contest&border=0&radius=12" alt="LeetCode stats" width="49%"/>
  </a>
  <a href="https://codeforces.com/profile/CODEFORCES_HANDLE">
    <img src="https://codeforces-readme-stats.vercel.app/api/card?username=CODEFORCES_HANDLE&theme=tokyonight&disable_animations=false&show_icons=true&force_username=true&border_color=00000000" alt="Codeforces stats" width="49%"/>
  </a>
</p>

<p align="center">
  <a href="https://codeforces.com/profile/CODEFORCES_HANDLE"><img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fcodeforces.com%2Fapi%2Fuser.info%3Fhandles%3DCODEFORCES_HANDLE&query=%24.result%5B0%5D.rating&label=Codeforces%20rating&logo=codeforces&color=1F8ACB&style=for-the-badge" alt="Codeforces rating (live)"/></a>
  <a href="https://codeforces.com/profile/CODEFORCES_HANDLE"><img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fcodeforces.com%2Fapi%2Fuser.info%3Fhandles%3DCODEFORCES_HANDLE&query=%24.result%5B0%5D.rank&label=rank&logo=codeforces&color=6A1B9A&style=for-the-badge" alt="Codeforces rank (live)"/></a>
  <a href="HDLBITS_URL"><img src="https://img.shields.io/badge/HDLBits-Verilog_practice-8A2BE2?style=for-the-badge" alt="HDLBits"/></a>
</p>

<p align="center"><sub>Ratings above are fetched live, so they are always current.</sub></p>

---

<!-- ═══════════════════════════  GITHUB STATS  ═══════════════════════════ -->

## 📊 GitHub in numbers

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=siddhaantxsingh&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&rank_icon=github" alt="GitHub stats" height="170"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=siddhaantxsingh&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" height="170"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=siddhaantxsingh&theme=tokyonight&hide_border=true" alt="GitHub streak" width="70%"/>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=siddhaantxsingh&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&column=7" alt="Trophies"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=siddhaantxsingh&theme=tokyo-night&hide_border=true&area=true" alt="Contribution graph" width="100%"/>
</p>

<!-- Snake: generated daily by .github/workflows/snake.yml -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/siddhaantxsingh/siddhaantxsingh/output/github-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/siddhaantxsingh/siddhaantxsingh/output/github-snake.svg"/>
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/siddhaantxsingh/siddhaantxsingh/output/github-snake-dark.svg"/>
  </picture>
</p>

---

<!-- ═══════════════════════════  PHILOSOPHY  ═══════════════════════════ -->

## 🧪 How I build

<table>
<tr>
<td align="center" width="25%">💥<br/><b>Break it on purpose</b><br/><sub>kill -9, power-loss images, bit flips, chaos tests</sub></td>
<td align="center" width="25%">🎯<br/><b>Check against a reference</b><br/><sub>PyTorch, Spike, llama.cpp, FAISS, RocksDB</sub></td>
<td align="center" width="25%">🧬<br/><b>Test the tests</b><br/><sub>mutation runs and injected bugs must fail the suite</sub></td>
<td align="center" width="25%">📏<br/><b>Say what isn't proven</b><br/><sub>every repo lists its own limitations</sub></td>
</tr>
</table>

---

<p align="center">
  <a href="https://www.linkedin.com/in/LINKEDIN_SLUG/"><b>LinkedIn</b></a> ·
  <a href="https://leetcode.com/u/LEETCODE_USERNAME/"><b>LeetCode</b></a> ·
  <a href="https://codeforces.com/profile/CODEFORCES_HANDLE"><b>Codeforces</b></a> ·
  <a href="https://www.codechef.com/users/CODECHEF_HANDLE"><b>CodeChef</b></a> ·
  <a href="HDLBITS_URL"><b>HDLBits</b></a> ·
  <a href="mailto:siddhaantxsingh@gmail.com"><b>Email</b></a> ·
  <a href="RESUME_URL"><b>Résumé</b></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E65100,35:6A1B9A,70:1565C0,100:0d1117&height=130&section=footer&text=From%20transistor%20to%20cloud.&fontSize=24&fontColor=ffffff&fontAlignY=68" alt="footer" width="100%"/>
</p>
