# Luigi Colella Garofalo

MSc student in Electrical and Electronics Engineering at EPFL, in Lausanne. Before that I did my Bachelor in Computer Science and Engineering at the University of Bologna, with exchanges at UC3M in Madrid and UC Santa Barbara.

I like working on the whole chip, from RTL to layout. On the design side I write RTL in SystemVerilog and C firmware for SoCs: this semester an OpenRISC system with caches on a Lattice ECP5 FPGA. On the implementation side I take RTL to a routed layout with Synopsys Fusion Compiler, and I write routing algorithms for 3D chips.

### Projects

- **[fast-3d-router](https://github.com/Bubagna/fast-3d-router)**: C++ router for the Partcl 3D routing challenge, for two hybrid-bonded dies. Negotiated congestion and local search, with results close to the top of the leaderboards in minutes on a laptop.
- **[spectre-riscv](https://github.com/Bubagna/spectre-riscv)**: 5-stage RV32I core in SystemVerilog with a dynamic branch predictor, checked instruction by instruction against a Python reference model. Work in progress, the plan is to run a Spectre v1 attack on it and fix it in hardware.
- **Dynamatic**: I'm adding an open-source synthesis and place and route flow (Yosys, nextpnr) to Dynamatic, the high-level synthesis compiler from EPFL that turns C code into dataflow circuits.

I also make small web apps for myself, like [shelf](https://github.com/Bubagna/shelf) for the books I read and [pocket](https://github.com/Bubagna/pocket) for my expenses.

[LinkedIn](https://www.linkedin.com/in/luigi-colella-garofalo)
