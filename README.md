<div align="center">

<!-- ═══════════════════════════════════════════════════  HEADER BANNER  ═══════════════════════════════════════════════════ -->

[![Header](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=48&pause=99999&color=FFFFFF&center=true&vCenter=true&width=800&height=90&lines=Monib+Mokhtari)](https://github.com/MonibMo)

[![Subtitle](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=400&size=15&pause=99999&color=A8D8E0&center=true&vCenter=true&width=800&height=30&lines=CEO+%40+Nexora+%7C+Embedded+Rust+Engineer+%7C+Electronics+%26+PCB+Designer)](https://github.com/MonibMo)

<!-- ═══════════════════════════════════════════════════  TYPING SVG  ═══════════════════════════════════════════════════ -->

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&pause=1000&color=58C4DC&center=true&vCenter=true&multiline=false&random=false&width=700&lines=Embedded+Systems+Architect+%F0%9F%A6%80;RTIC+v2+Expert+%7C+Real-Time+Firmware+Engineer;Analog+%26+Digital+Electronics+Specialist;Schematic+%26+PCB+Designer+%F0%9F%96%A7;Industrial+Microcontroller+Systems+%F0%9F%8F%AD;Computer+Architecture+%26+Embedded+OS+Patterns)](https://git.io/typing-svg)

<br/>

<!-- ═══════════════════════════════════════════════════  PROFILE VIEWS & SOCIAL  ═══════════════════════════════════════════════════ -->

[![Profile Views](https://komarev.com/ghpvc/?username=MonibMo&label=Profile+Views&color=0e75b6&style=for-the-badge)](https://github.com/MonibMo)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Monib%20Mokhtari-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/monib-mokhtari-148102390)
[![GitHub followers](https://img.shields.io/github/followers/MonibMo?label=Followers&style=for-the-badge&color=2c5364&logo=github)](https://github.com/MonibMo?tab=followers)

</div>

---

<!-- ═══════════════════════════════════════════════════  ABOUT  ═══════════════════════════════════════════════════ -->

## 🧠 About Me

```rust
#![no_std]
#![no_main]

use rtic::app;
use nexora::prelude::*;

pub struct Monib {
    role:        &'static str,
    company:     &'static str,
    location:    &'static str,
    expertise:   [&'static str; 6],
    philosophy:  &'static str,
}

impl Monib {
    pub const fn new() -> Self {
        Self {
            role:     "CEO & Embedded Systems Architect",
            company:  "Nexora",
            location: "Berlin, Germany 🇩🇪",
            expertise: [
                "Embedded Rust · RTIC v2 · Real-Time Systems",
                "Analog & Digital Electronics Design",
                "Schematic & PCB Layout (industrial grade)",
                "Computer Architecture & Embedded OS Patterns",
                "Industrial Microcontrollers (STM32, nRF, AVR ...)",
                "Engineering Leadership & Technical Management",
            ],
            philosophy: "Build firmware so correct, the hardware never lies.",
        }
    }
}

#[app(device = nexora_bsp, peripherals = true, dispatchers = [EXTI0])]
mod app {
    #[init]
    fn init(cx: init::Context) -> (Shared, Local) {
        Monib::new().boot(cx);   // 🚀 Always running
    }
}
```

---

<!-- ═══════════════════════════════════════════════════  SKILL BARS  ═══════════════════════════════════════════════════ -->

## 🔬 Core Competencies

<div align="center">

| Domain | Proficiency |
|---|---|
| **Embedded Rust / RTIC v2** | ████████████████████ 100% |
| **Analog & Digital Electronics** | ████████████████████ 100% |
| **PCB & Schematic Design** | ████████████████████ 100% |
| **Computer Architecture** | ███████████████████░ 95% |
| **Industrial MCU Systems** | ████████████████████ 100% |
| **Embedded Design Patterns** | ███████████████████░ 95% |
| **Technical Leadership** | ████████████████████ 100% |
| **Linux / RTOS / Bare-Metal** | ██████████████████░░ 90% |

</div>

---

<!-- ═══════════════════════════════════════════════════  TECH STACK  ═══════════════════════════════════════════════════ -->

## ⚙️ Tech Stack & Toolbox

### 🦀 Languages & Runtimes

![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly-525252?style=for-the-badge&logo=assemblyscript&logoColor=white)

### 🧱 Embedded Frameworks & Crates

![RTIC v2](https://img.shields.io/badge/RTIC%20v2-Expert-black?style=for-the-badge&logo=rust&logoColor=orange)
![embedded-hal](https://img.shields.io/badge/embedded--hal-4.x-orange?style=for-the-badge&logo=rust&logoColor=white)
![embassy](https://img.shields.io/badge/Embassy-Async%20Embedded-5c2d91?style=for-the-badge&logo=rust&logoColor=white)
![cortex-m](https://img.shields.io/badge/cortex--m-0891b2?style=for-the-badge&logo=arm&logoColor=white)
![defmt](https://img.shields.io/badge/defmt-logging-22c55e?style=for-the-badge&logo=rust&logoColor=white)
![probe-rs](https://img.shields.io/badge/probe--rs-debug-dc2626?style=for-the-badge&logo=rust&logoColor=white)

### 🔧 Microcontrollers & Hardware Platforms

![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![nRF52](https://img.shields.io/badge/nRF52xx-00A9CE?style=for-the-badge&logo=nordicsemiconductor&logoColor=white)
![AVR / ATmega](https://img.shields.io/badge/AVR%20%2F%20ATmega-FF8000?style=for-the-badge&logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=for-the-badge&logo=riscv&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![ARM Cortex](https://img.shields.io/badge/ARM%20Cortex--M%2FR%2FA-0091BD?style=for-the-badge&logo=arm&logoColor=white)

### 🖥️ Electronics & Hardware Design

![Altium](https://img.shields.io/badge/Altium%20Designer-A5915F?style=for-the-badge&logo=altiumdesigner&logoColor=white)
![SolidWorks](https://img.shields.io/badge/SolidWorks-FF0000?style=for-the-badge&logo=dassaultsystemes&logoColor=white)
![LTspice](https://img.shields.io/badge/LTspice-Simulation-8B0000?style=for-the-badge&logoColor=white)
![Oscilloscope](https://img.shields.io/badge/Oscilloscope-Debug-2c5364?style=for-the-badge&logoColor=white)
![JTAG/SWD](https://img.shields.io/badge/JTAG%20%2F%20SWD-Debugging-555?style=for-the-badge&logoColor=white)

### 🛠️ Dev Tools & Environment

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![cargo](https://img.shields.io/badge/Cargo-Build%20System-e67e22?style=for-the-badge&logo=rust&logoColor=white)
![GDB](https://img.shields.io/badge/GDB-Debug-red?style=for-the-badge&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white)

---

<!-- ═══════════════════════════════════════════════════  EXPERTISE DEEP DIVE  ═══════════════════════════════════════════════════ -->

## 🏗️ Areas of Deep Expertise

<table>
<tr>
<td width="50%">

### ⚡ Real-Time Firmware (RTIC v2)
- **RTIC v2** task scheduling & priority inversion prevention
- Hardware task binding, software task dispatchers
- Shared resource management with compile-time deadlock freedom
- Monotonic timers, async RTIC tasks
- Zero-cost abstractions on Cortex-M with zero RTOS overhead
- Memory-safe ISR design patterns

</td>
<td width="50%">

### 🔌 Analog & Digital Electronics
- Op-amp circuits, filter design (active / passive)
- Power electronics: regulators, converters (buck/boost)
- High-speed digital signal integrity
- Noise-immune sensor front-ends
- Mixed-signal PCB layout rules (ground planes, decoupling)
- EMI/EMC considerations for industrial environments

</td>
</tr>
<tr>
<td width="50%">

### 🖥️ Computer Architecture
- Von Neumann vs Harvard pipeline trade-offs
- Cache hierarchy, memory-mapped I/O, DMA engines
- RISC vs CISC ISA for embedded targets
- MPU/MMU configuration for bare-metal safety
- Bootloader design & secure firmware update (DFU/OTA)
- CMSIS, vendor HAL layer dissection

</td>
<td width="50%">

### 🏭 Industrial MCU Systems
- IEC-certified safety considerations (functional safety)
- CAN / CAN-FD, Modbus, RS-485, LIN bus protocols
- Watchdog & fault-detection state machines
- Real-time data acquisition at industrial tolerances
- Long-lifetime deployment firmware strategies
- BMS, motor control, sensor-fusion systems

</td>
</tr>
<tr>
<td width="50%">

### 🗂️ Embedded Design Patterns
- Type-state machines at zero runtime cost
- RAII resource ownership for peripheral management
- Builder pattern for configuration structs
- Actor model with RTIC task isolation
- Error propagation with `defmt` & `embedded-error`
- `#[no_std]` portable driver architecture

</td>
<td width="50%">

### 🏢 Engineering Leadership
- Building & managing embedded engineering teams
- Architecture reviews & technical decision ownership
- Roadmap planning from prototype → production
- Cross-functional collaboration (HW ↔ FW ↔ SW)
- Code-review culture & documentation standards
- Open-source crate maintenance & ecosystem contributions

</td>
</tr>
</table>

---

<!-- ═══════════════════════════════════════════════════  OPEN SOURCE  ═══════════════════════════════════════════════════ -->

## 📦 Open Source Projects

<div align="center">

[![Rotary Library](https://github-readme-stats.vercel.app/api/pin/?username=MonibMo&repo=Rotary_Library&theme=github_dark&border_color=58C4DC&title_color=58C4DC&icon_color=f97316&show_owner=true)](https://github.com/MonibMo/Rotary_Library)
[![hd44780-embedded-hal](https://github-readme-stats.vercel.app/api/pin/?username=MonibMo&repo=hd44780-embedded-hal&theme=github_dark&border_color=58C4DC&title_color=58C4DC&icon_color=f97316&show_owner=true)](https://github.com/MonibMo/hd44780-embedded-hal)

</div>

---

<!-- ═══════════════════════════════════════════════════  GITHUB STATS  ═══════════════════════════════════════════════════ -->

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=MonibMo&show_icons=true&theme=github_dark&border_color=30363d&title_color=58C4DC&icon_color=f97316&text_color=c9d1d9&include_all_commits=true&count_private=true&hide_border=false" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MonibMo&layout=compact&theme=github_dark&border_color=30363d&title_color=58C4DC&text_color=c9d1d9&langs_count=6" />

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=MonibMo&theme=github-dark-blue&border=30363d&ring=58C4DC&fire=f97316&currStreakLabel=58C4DC)](https://git.io/streak-stats)

</div>

---

<!-- ═══════════════════════════════════════════════════  KNOWLEDGE MAP  ═══════════════════════════════════════════════════ -->

## 🗺️ Knowledge Map

```
                        ┌─────────────────────────────────────┐
                        │         MONIB MOKHTARI               │
                        │     Embedded Systems Architect        │
                        └──────────────┬──────────────────────┘
                                       │
          ┌────────────────────────────┼────────────────────────────┐
          │                            │                            │
   ┌──────▼──────┐             ┌───────▼───────┐           ┌───────▼───────┐
   │  FIRMWARE   │             │  ELECTRONICS  │           │  LEADERSHIP   │
   │─────────────│             │───────────────│           │───────────────│
   │ RTIC v2     │             │ Analog Design │           │ CEO Nexora    │
   │ embedded-hal│             │ Digital Logic │           │ Team Building │
   │ async Rust  │             │ PCB Layout    │           │ Arch Decisions│
   │ no_std      │             │ Schematics    │           │ Product Road  │
   │ DMA / ISR   │             │ EMC / SI      │           │ map Planning  │
   └──────┬──────┘             └───────┬───────┘           └───────┬───────┘
          │                            │                            │
   ┌──────▼──────┐             ┌───────▼───────┐           ┌───────▼───────┐
   │  PROTOCOLS  │             │  PLATFORMS    │           │  CS THEORY    │
   │─────────────│             │───────────────│           │───────────────│
   │ CAN / CANFD │             │ STM32 family  │           │ CPU Arch      │
   │ Modbus      │             │ nRF52xx       │           │ OS Concepts   │
   │ RS-485      │             │ AVR / ATmega  │           │ Type Theory   │
   │ SPI/I2C/UAR │             │ ESP32 / RISC-V│           │ Memory Models │
   │ USB / JTAG  │             │ Cortex-M/R/A  │           │ Design Pattns │
   └─────────────┘             └───────────────┘           └───────────────┘
```

---

<!-- ═══════════════════════════════════════════════════  PHILOSOPHY  ═══════════════════════════════════════════════════ -->

## 💡 Engineering Philosophy

<div align="center">

> *"If the compiler agrees, the hardware will agree. Write firmware so precise that even silence on the bus is intentional."*
>
> — **Monib Mokhtari**

</div>

```rust
// The Embedded Engineer's Creed
fn engineer_creed() {
    assert!(memory_is_owned_not_borrowed());     // Rust ownership = no UAF, ever
    assert!(every_interrupt_has_a_priority());   // RTIC v2 priority ceiling protocol
    assert!(no_undefined_behavior_in_isr());     // cortex-m critical sections
    assert!(pcb_tells_the_same_story_as_code()); // schematic ↔ firmware consistency
    assert!(the_team_ships_together());           // leadership is a protocol too
}
```

---

<!-- ═══════════════════════════════════════════════════  CONNECT  ═══════════════════════════════════════════════════ -->

## 🤝 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/monib-mokhtari-148102390)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MonibMo)
[![Nexora](https://img.shields.io/badge/Nexora-Website-2c5364?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAyQzYuNDggMiAyIDYuNDggMiAxMnM0LjQ4IDEwIDEwIDEwIDEwLTQuNDggMTAtMTBTMTcuNTIgMiAxMiAyem0tMiAxNWwtNS01IDEuNDEtMS40MUwxMCAxNC4xN2w3LjU5LTcuNTlMMTkgOGwtOSA5eiIvPjwvc3ZnPg==)](https://nexora-embedded.com)
[![Phone](https://img.shields.io/badge/Phone-%2B98%20933%20553%205372-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:+989335535372)

</div>

<br/>

<div align="center">

**Open to:**
![Collaboration](https://img.shields.io/badge/Open%20Source-Collaboration-22c55e?style=flat-square)
![Consulting](https://img.shields.io/badge/Embedded-Consulting-0891b2?style=flat-square)
![Speaking](https://img.shields.io/badge/Tech-Talks%20%26%20Speaking-f97316?style=flat-square)
![Research](https://img.shields.io/badge/Industrial-Research-8b5cf6?style=flat-square)

</div>

---

<div align="center">

*Built with* 🦀 *Rust — memory-safe from header to footer.*

</div>
