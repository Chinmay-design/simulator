# T Flip-Flop & Adder Simulator

An interactive digital logic simulator built for the CIA III Digital Logic Design
project (CHRIST Deemed to Be University).

Covers four modules, each with adjustable binary inputs and a live explanation panel:

- **T Flip-Flop** — edge-triggered toggle flip-flop (Q changes on a clock pulse when T = 1)
- **Half Adder** — Sum = A ⊕ B, Carry = A · B
- **Full Adder** — Sum = A ⊕ B ⊕ Cin, Cout = AB + BCin + ACin
- **4-Bit Ripple-Carry Adder** — four Full Adders chained together to add two 4-bit binary numbers, demonstrating the building block of an ALU

## Try it live

Open [`index.html`](./index.html) directly, or enable **GitHub Pages** for this repo
(Settings → Pages → Deploy from branch `main` / root) to get a shareable link.

## Tech

Single self-contained HTML file — vanilla JavaScript and inline SVG, no build step
or dependencies required.

## Authors

Chinmay R, Hemanth S Yadav — 1 BCA A, Department of Computer Science
