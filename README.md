# Ben Eater's 8-bit Computer Project

This repository documents my journey in building and experimenting with Ben Eater's 8-bit computer. The project is built using Transistor-Transistor Logic (TTL) chips on a breadboard, and I'm currently in the development stage.

## Overview

The 8-bit computer is inspired by Ben Eater's excellent tutorials and uses 74HC series chips. Some modifications have been made to work around the lack of internal pull-up resistors in HC chips by adding external pull-up resistors.

### Current Status

I have completed the following modules:

- **Clock Module**: Designed a clock with adjustable frequency.
- **ALU (Arithmetic Logic Unit)**: Built a fully functional ALU for basic arithmetic and logic operations.
- **RAM (Random Access Memory)**: Implemented a memory module using TTL chips.
- **ROM (Read-Only Memory)**: Programmed ROM to store machine instructions.

### Tools and Resources

- **CRUMB Software**: Initially used for planning and testing circuits. Recently updated to support HC series chips.
- **74HC Series Chips**: Used throughout the project with external pull-up resistors to compensate for design differences.
- **Breadboard and Wires**: For physical prototyping.

### Challenges Faced

- Adapting the 74HC series chips to behave similarly to LS series chips by using external pull-up resistors.
- Debugging circuit connections on the breadboard.

### Future Plans

- Add an I/O interface for basic input and output.
- Integrate a display for visualizing data.
- Optimize and clean up the wiring on the breadboard for better reliability.
- Write detailed documentation for each module.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ben-eater-8bit-computer.git
   ```

2. Explore the directories for individual modules:
   - `/clock`
   - `/alu`
   - `/ram`
   - `/rom`

3. Refer to the `README` files in each module for specific details and instructions.

## Acknowledgments

- Special thanks to Ben Eater for his incredible tutorials.
- CRUMB Software by Mike Bushell for circuit visualization.

## Contributing

Since this project is still under development, contributions and suggestions are welcome. Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Stay tuned for updates as I continue to build and refine this project!
