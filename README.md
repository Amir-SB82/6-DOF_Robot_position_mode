# position mode

                                            +---------------+
                                            | position mode |
                                            +---------------+
## Overview

**position mode** It is an important control mode used in control loops.It can also play a good role in setting the initial position of the trajectories.   

---

## Features

- ⚡ **SDO message**: you can send position with SDO message because the drive needs to receive the message only once.For this reason, there is no traffic on the can bus.
- ◆ If you want to see the position of the sent message, you should plot it in STMstudio.
---

## Getting Started

To set up the project locally, follow these steps.

### Prerequisites
- **STM32CubeIDE**: Ensure you have [STM32CubeIDE version 1.13.0(recommended)]
- **CANopen stack**: you need this stack for your communication 
i have used this stack in the code, you can also download and including it from [github website](https://github.com/CANopenNode/CANopenNode)

### Run code
1. **open new project**: 
    go to file --> new --> STM32 project
2. **add the stack**: 
    Go to project --> properties --> paths and symbols --> includs --> add --> file systrm
    Then choose CANopenNode and core/CANopenNode_STM32
    Ensure there is CANopenNode in the source location(if this file does not exist in the source location, first apply and close and build the project, then come to the source location again.)
3. **run**:
    now, you can use this mode by upload the code to micro.

---

## License
- you can download
 *CANopenNode* document from this link(https://drive.google.com/file/d/1Lg_B5r14P_CGMcFEsO6PIyp6nOz_elqh/view?usp=drive_link)

---

## Contact
- **Email**: bestbs.1382@gmail.com
- **Github**: Amir-SB82