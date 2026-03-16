# enuzzo

[![Studio](https://img.shields.io/badge/Netmilk_Studio-Creative_Director-7551FF?style=for-the-badge)](https://netmilk.studio)
[![Hardware](https://img.shields.io/badge/ESP32-Too_Many-E7352C?style=for-the-badge&logo=espressif&logoColor=white)](#things-with-screens)
[![Pi](https://img.shields.io/badge/Raspberry_Pi-Also_Too_Many-C51A4A?style=for-the-badge&logo=raspberrypi&logoColor=white)](#things-with-screens)
[![Rust](https://img.shields.io/badge/Rust-Learning_by_Shipping-000000?style=for-the-badge&logo=rust&logoColor=white)](#things-without-screens)
[![License](https://img.shields.io/badge/License-MIT_(mostly)-10B981?style=for-the-badge)](#license)

> Creative Director by title. Person who plugs things into other things until they glow, by vocation.

I design and build things at **[Netmilk Studio](https://netmilk.studio)** — a graphic design and product studio in southern Switzerland where the line between "client project" and "desk full of microcontrollers" has been blurred beyond recognition since approximately 2019.

The work spans from brand systems and WordPress sites that pay the rent, to ESP32 firmware and Raspberry Pi installations that don't. Both are treated with the same care. One of them involves more soldering.

---

## Things With Screens

Hardware projects that started as weekend experiments and somehow grew documentation.

| Project | What | Hardware | Status |
|---|---|---|---|
| **[ScryBar](https://github.com/enuzzo/scrybar)** | Word clock in 13 languages (including Klingon), RSS, Wikipedia, weather, and DOOM. On a 3.49" desk bar. | ESP32-S3, AXS15231B 640×172 | Alive and telling time in Latin |
| **[Retina Cannon](https://github.com/enuzzo/retinacannon)** | Real-time camera-to-shader visual engine. 11 effects, zero X server, one HDMI cable, instant party credibility. | Raspberry Pi 5, IMX219 | Actively melting retinas |
| **[TaleVision](https://github.com/enuzzo/talevision)** | E-ink ambient display. LitClock mode (literary quotes synced to actual time) + SlowMovie mode (one frame every few minutes). | Pi Zero W, Inky Impression 4" | Rendering Koyaanisqatsi, one frame at a time |

## Things Without Screens

Or at least, things where the screen is someone else's problem.

| Project | What | Stack |
|---|---|---|
| **[PRTCL](https://prtcl.es)** | Particle effect playground. Visual editor, text-to-particles with Google Fonts, dual export (full HTML + headless Elementor snippet). For anyone who wants animated particles on a website and doesn't want to learn WebGL. | Next.js 15, React Three Fiber, shadcn/ui |
| **[CRUST](https://github.com/enuzzo/crust)** | Card + Rust. CLI tool for vCard 4.0 generation and QR code output. Because every agency eventually needs to batch-generate contact cards and the existing tools are all either abandoned or written in PHP. | Rust |
| **Vibemilk** | The Netmilk design system. 270 CSS tokens, 10 themes, exports to JSON/Swift/Rust/C(RGB565)/Elementor. Works on a 3.49" ESP32 display and a full website with the same token file. | CSS custom properties, zero dependencies |
| **Cowsmos** | Netmilk's internal management system. Time tracking, project management, invoicing. Named after cows because studio branding is a lifestyle. | Next.js 15, PostgreSQL, Drizzle, Better Auth |

## The Stack, Loosely

Not a tech stack in the traditional "I list frameworks on my LinkedIn" sense. More of a "these are the tools I actually open every day" sense.

**Design:** Figma, Midjourney, pen and paper when the screen gets too bright.
**Code:** TypeScript, Rust (getting there), Python, CSS that has opinions.
**Hardware:** ESP32 (C3, S3, too many variants), Raspberry Pi (Zero W through 5), WLED, Home Assistant, 3D printing (Bambu Lab A1).
**Web:** Next.js, WordPress/Elementor (for client work, willingly), Tailwind, Drizzle.
**Tools:** Claude Code, Bear, VS Code, Kaku, a terminal that never closes.

---

## About Netmilk Studio

Small studio, Italian-speaking Switzerland, near the lakes. We do design, branding, web, and increasingly weird hardware things. The team is small. The project range is not. Clients get brand systems and WordPress sites; the studio gets ESP32 prototypes and ambient computing experiments. Everyone seems happy with this arrangement.

**[netmilk.studio](https://netmilk.studio)**

---

## License

Most things here are MIT. Use them, fork them, put them on hardware that costs less than lunch. Attribution appreciated. Don't ask me to debug your fork at 2am.

---

<div align="center">

*Built with solder, CSS custom properties, an mass of Raspberry Pis,*
*and the unwavering belief that a word clock in Klingon on a desk bar*
*is a legitimate use of an engineering degree you don't have.*

</div>
