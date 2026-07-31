![Open-CMSIS-Pack](/profile/Open-CMSIS-Pack.png)

## About Open-CMSIS-Pack

The [Open-CMSIS-Pack project](https://open-cmsis-pack.org) offers a flexible and easy to use end to end development
flow for embedded software - from project creation to software execution on real or virtual hardware.

## List of Repositories

### Specifications

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [Open-CMSIS-Pack-Spec](https://github.com/Open-CMSIS-Pack/Open-CMSIS-Pack-Spec) | A specification describing a delivery mechanism for software components, device parameters, and evaluation board support. It also defines the build tools for projects based on software packs. | Access the [pre-built specification directly](https://open-cmsis-pack.github.io/Open-CMSIS-Pack-Spec/main/html/index.html). |
| [Open-CMSIS-SVD-Spec](https://github.com/Open-CMSIS-Pack/svd-spec) | A specification for describing the system memory mapped registers and peripherals of devices (for example microcontrollers). | Access the [pre-built specification directly](https://open-cmsis-pack.github.io/svd-spec/main/index.html). |
| [Debug Adapter Registry](https://github.com/Open-CMSIS-Pack/debug-adapter-registry) | Provides a list of supported debuggers with VS Code launch.json/tasks.json template. | Refer to the [Readme.md](https://github.com/Open-CMSIS-Pack/debug-adapter-registry) file. |
| [Open-CMSIS-Pack-Taxonomy](https://github.com/Open-CMSIS-Pack/Open-CMSIS-Pack-Taxonomy) | Organizes Cclass and Cgroup definitions to access software [\<components\>](https://open-cmsis-pack.github.io/Open-CMSIS-Pack-Spec/main/html/pdsc_components_pg.html) and application programming interfaces [\<apis\>](https://open-cmsis-pack.github.io/Open-CMSIS-Pack-Spec/main/html/pdsc_apis_pg.html). | Refer to the [Readme.md](https://github.com/Open-CMSIS-Pack/Open-CMSIS-Pack-Taxonomy) file. |

### Ready-to-use Tools

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [CMSIS-Toolbox](https://github.com/Open-CMSIS-Pack/cmsis-toolbox) | A set of command-line tools for software packs. | The [documentation](https://open-cmsis-pack.github.io/cmsis-toolbox/installation) explains the download, installation, and configuration process. |
| [gen-pack](https://github.com/Open-CMSIS-Pack/gen-pack) | A library for scripts creating Open-CMSIS-Packs. | Refer to the [Readme.md](https://github.com/Open-CMSIS-Pack/gen-pack) file. |
| [gen-pack-action](https://github.com/Open-CMSIS-Pack/gen-pack-action) | A GitHub workflow action generating documentation and Open-CMSIS-Packs. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/gen-pack-action). |

### VS Code Extensions

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [CMSIS Solution](https://github.com/Open-CMSIS-Pack/vscode-cmsis-solution) | A VS Code extension for project management and build based on the CMSIS-Toolbox. | The [documentation](https://github.com/Open-CMSIS-Pack/vscode-cmsis-solution/blob/main/README.md) provides an overview of features and usage. |
| [CMSIS Debugger](https://github.com/Open-CMSIS-Pack/vscode-cmsis-debugger) | A VS Code extension pack to enable debugging Arm Cortex-M processor-based devices using the GDB/MI protocol. | The [documentation](https://github.com/Open-CMSIS-Pack/vscode-cmsis-debugger/blob/main/README.md) provides an overview of features and usage. |

### CMSIS-Toolbox Project Examples (*csolution projects*)

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [csolution-examples](https://github.com/Open-CMSIS-Pack/csolution-examples) | A collection of exemplary csolution-based projects. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/csolution-examples). |
| [vscode-get-started](https://github.com/Open-CMSIS-Pack/vscode-get-started) | Setup of VS Code environment along with an example project. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/vscode-get-started). |

### Tutorials for Creating Own Software Packs (Webinar Recordings in Readme.md)

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [Create-Scaleable-SW](https://github.com/Open-CMSIS-Pack/Create-Scalable-SW)   | Explains how to structure complex middleware stacks. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/Create-Scalable-SW). |
| [GSP-Pack-HandsOn](https://github.com/Open-CMSIS-Pack/GSP-Pack-HandsOn)   | Explains the steps to create a generic software pack. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/GSP-Pack-HandsOn). |
| [DFP-Pack-HandsOn](https://github.com/Open-CMSIS-Pack/DFP-Pack-HandsOn) | Explains the steps to create a device family pack. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/DFP-Pack-HandsOn). |
| [BSP-Pack-HandsOn](https://github.com/Open-CMSIS-Pack/BSP-Pack-HandsOn) | Explains the steps to create a board support pack. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/BSP-Pack-HandsOn). |

### NXP Pack with Project Templates

| Repository | Pack Link   | Description  |
|------------|-------------|--------------|
| [NXP_FRDM-MCXN947_BSP](https://github.com/open-cmsis-pack/NXP_FRDM-MCXN947_BSP)  | experimental - use local repository | BSP for NXP_FRDM-MCXN947 |

### STM32 Packs with Generator Support

The following software packs support the [STM32CubeMX integration](https://github.com/Open-CMSIS-Pack/cmsis-toolbox/blob/main/docs/CubeMX.md) of the CMSIS-Toolbox. These packs are compatible with uVision v5.40 or higher. The packs support Arm Compiler 6, GCC, and IAR. LLVM is not supported due to STM32CubeMX restrictions. Many Board Support Packs contain software layers for [MDK-Middleware](https://www.keil.arm.com/packs/mdk-middleware-keil/overview/); refer to the pack link for more information.

| Repository | Pack Link   | Description  |
|------------|-------------|--------------|
| **DFP**    | [keil.arm.com/devices](https://www.keil.arm.com/devices/)  | Device Family Packs |
| [STM32C0xx_DFP](https://github.com/Open-CMSIS-Pack/STM32C0xx_DFP) | [keil.arm.com/packs/stm32c0xx_dfp-keil](https://www.keil.arm.com/packs/stm32c0xx_dfp-keil) | STM32C0 Series |
| [STM32F4xx_DFP](https://github.com/Open-CMSIS-Pack/STM32F4xx_DFP) | [keil.arm.com/packs/stm32f4xx_dfp-keil](https://www.keil.arm.com/packs/stm32f4xx_dfp-keil) | STM32F4 Series |
| [STM32F0xx_DFP](https://github.com/Open-CMSIS-Pack/STM32F0xx_DFP) | [keil.arm.com/packs/stm32f0xx_dfp-keil](https://www.keil.arm.com/packs/stm32f0xx_dfp-keil) | STM32F0 Series |
| [STM32F2xx_DFP](https://github.com/Open-CMSIS-Pack/STM32F2xx_DFP) | [keil.arm.com/packs/stm32f2xx_dfp-keil](https://www.keil.arm.com/packs/stm32f2xx_dfp-keil) | STM32F2 Series |
| [STM32F3xx_DFP](https://github.com/Open-CMSIS-Pack/STM32F3xx_DFP) | [keil.arm.com/packs/stm32f3xx_dfp-keil](https://www.keil.arm.com/packs/stm32f3xx_dfp-keil) | STM32F3 Series |
| [STM32F7xx_DFP](https://github.com/Open-CMSIS-Pack/STM32F7xx_DFP) | [keil.arm.com/packs/stm32f7xx_dfp-keil](https://www.keil.arm.com/packs/stm32f7xx_dfp-keil) | STM32F7 Series |
| [STM32G0xx_DFP](https://github.com/Open-CMSIS-Pack/STM32G0xx_DFP) | [keil.arm.com/packs/stm32g0xx_dfp-keil](https://www.keil.arm.com/packs/stm32g0xx_dfp-keil) | STM32G0 Series |
| [STM32G4xx_DFP](https://github.com/Open-CMSIS-Pack/STM32G4xx_DFP) | [keil.arm.com/packs/stm32g4xx_dfp-keil](https://www.keil.arm.com/packs/stm32g4xx_dfp-keil) | STM32G4 Series |
| [STM32H5xx_DFP](https://github.com/Open-CMSIS-Pack/STM32H5xx_DFP) | [keil.arm.com/packs/stm32h5xx_dfp-keil](https://www.keil.arm.com/packs/stm32h5xx_dfp-keil) | STM32H5 Series |
| [STM32H7xx_DFP](https://github.com/Open-CMSIS-Pack/STM32H7xx_DFP) | [keil.arm.com/packs/stm32h7xx_dfp-keil](https://www.keil.arm.com/packs/stm32h7xx_dfp-keil) | STM32H7 Series |
| [STM32H7RSxx_DFP](https://github.com/Open-CMSIS-Pack/STM32H7RSxx_DFP) | [keil.arm.com/packs/stm32h7rsxx_dfp-keil](https://www.keil.arm.com/packs/stm32h7rsxx_dfp-keil) | STM32H7RS Series |
| [STM32L0xx_DFP](https://github.com/Open-CMSIS-Pack/STM32L0xx_DFP) | [keil.arm.com/packs/stm32l0xx_dfp-keil](https://www.keil.arm.com/packs/stm32l0xx_dfp-keil) | STM32L0 Series |
| [STM32L1xx_DFP](https://github.com/Open-CMSIS-Pack/STM32L1xx_DFP) | [keil.arm.com/packs/stm32l1xx_dfp-keil](https://www.keil.arm.com/packs/stm32l1xx_dfp-keil) | STM32L1 Series |
| [STM32L4xx_DFP](https://github.com/Open-CMSIS-Pack/STM32L4xx_DFP) | [keil.arm.com/packs/stm32l4xx_dfp-keil](https://www.keil.arm.com/packs/stm32l4xx_dfp-keil) | STM32L4 Series |
| [STM32L5xx_DFP](https://github.com/Open-CMSIS-Pack/STM32L5xx_DFP) | [keil.arm.com/packs/stm32l5xx_dfp-keil](https://www.keil.arm.com/packs/stm32l5xx_dfp-keil) | STM32L5 Series |
| [STM32N6xx_DFP](https://github.com/Open-CMSIS-Pack/STM32N6xx_DFP) | [keil.arm.com/packs/stm32n6xx_dfp-keil](https://www.keil.arm.com/packs/stm32n6xx_dfp-keil) | STM32N6 Series |
| [STM32U0xx_DFP](https://github.com/Open-CMSIS-Pack/STM32U0xx_DFP) | [keil.arm.com/packs/stm32u0xx_dfp-keil](https://www.keil.arm.com/packs/stm32u0xx_dfp-keil) | STM32U0 Series |
| [STM32U3xx_DFP](https://github.com/Open-CMSIS-Pack/STM32U3xx_DFP) | [keil.arm.com/packs/stm32u3xx_dfp-keil](https://www.keil.arm.com/packs/stm32u3xx_dfp-keil) | STM32U3 Series |
| [STM32U5xx_DFP](https://github.com/Open-CMSIS-Pack/STM32U5xx_DFP) | [keil.arm.com/packs/stm32u5xx_dfp-keil](https://www.keil.arm.com/packs/stm32u5xx_dfp-keil) | STM32U5 Series |
| [STM32WBxx_DFP](https://github.com/Open-CMSIS-Pack/STM32WBxx_DFP) | [keil.arm.com/packs/stm32wbxx_dfp-keil](https://www.keil.arm.com/packs/stm32wbxx_dfp-keil) | STM32WB Series |
| [STM32WBAxx_DFP](https://github.com/Open-CMSIS-Pack/STM32WBAxx_DFP) | [keil.arm.com/packs/stm32wbaxx_dfp-keil](https://www.keil.arm.com/packs/stm32wbaxx_dfp-keil) | STM32WBA Series |
| [STM32WB0x_DFP](https://github.com/Open-CMSIS-Pack/STM32WB0x_DFP) | [keil.arm.com/packs/stm32wb0x_dfp-keil](https://www.keil.arm.com/packs/stm32wb0x_dfp-keil) | STM32WB0 Series |
| [STM32WLxx_DFP](https://github.com/Open-CMSIS-Pack/STM32WLxx_DFP) | [keil.arm.com/packs/stm32wlxx_dfp-keil](https://www.keil.arm.com/packs/stm32wlxx_dfp-keil) | STM32WL Series |
| [STM32WL3x_DFP](https://github.com/Open-CMSIS-Pack/STM32WL3x_DFP) | [keil.arm.com/packs/stm32wl3x_dfp-keil](https://www.keil.arm.com/packs/stm32wl3x_dfp-keil) | STM32WL3 Series |
| [STM32WL4x_DFP](https://github.com/Open-CMSIS-Pack/STM32WL4x_DFP) | [keil.arm.com/packs/stm32wl4x_dfp-keil](https://www.keil.arm.com/packs/stm32wl4x_dfp-keil) | STM32WL4 Series |
| **CMSIS-Driver**    | .  | . |
| [CMSIS-Driver_STM32](https://github.com/Open-CMSIS-Pack/CMSIS-Driver_STM32) | [keil.arm.com/packs/cmsis-driver_stm32-arm](https://www.keil.arm.com/packs/cmsis-driver_stm32-arm) | Shim layers: STM32HAL to CMSIS-Driver |
| **BSP**    | [keil.arm.com/boards](https://www.keil.arm.com/boards/)  | Board Support Packs |
| STM32F4 | . | . |
| [NUCLEO-F401RE_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-F401RE_BSP) | [keil.arm.com/packs/nucleo-f401re_bsp-keil](https://www.keil.arm.com/packs/nucleo-f401re_bsp-keil) | Nucleo Kit for STM32F401RE |
| [NUCLEO-F412ZG_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-F412ZG_BSP) | [keil.arm.com/packs/nucleo-f412zg_bsp-keil](https://www.keil.arm.com/packs/nucleo-f412zg_bsp-keil) | Nucleo Kit for STM32F412ZG |
| [NUCLEO-F429ZI_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-F429ZI_BSP) | [keil.arm.com/packs/nucleo-f429zi_bsp-keil](https://www.keil.arm.com/packs/nucleo-f429zi_bsp-keil) | Nucleo Kit for STM32F429ZI |
| [NUCLEO-F446RE_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-F446RE_BSP) | [keil.arm.com/packs/nucleo-f446re_bsp-keil](https://www.keil.arm.com/packs/nucleo-f446re_bsp-keil) | Nucleo Kit for STM32F446RE |
| [STM32F469I-DISCO_BSP](https://github.com/Open-CMSIS-Pack/STM32F469I-DISCO_BSP) | [keil.arm.com/packs/stm32f469i-disco_bsp-keil](https://www.keil.arm.com/packs/stm32f469i-disco_bsp-keil) | Discovery Kit for STM32F469I |
| [STM32F407G-DISC1_BSP](https://github.com/Open-CMSIS-Pack/STM32F407G-DISC1_BSP) | [keil.arm.com/packs/stm32f407g-disc1_bsp-keil](https://www.keil.arm.com/packs/stm32f407g-disc1_bsp-keil) | Discovery Kit for STM32F407G |
| [STM32F429I-DISC1_BSP](https://github.com/Open-CMSIS-Pack/STM32F429I-DISC1_BSP) | [keil.arm.com/packs/stm32f429i-disc1_bsp-keil](https://www.keil.arm.com/packs/stm32f429i-disc1_bsp-keil) | Discovery Kit for STM32F429I |
| STM32L4 | . | . |
| [B-L475E-IOT01A_BSP](https://github.com/Open-CMSIS-Pack/ST_B-L475E-IOT01A_BSP) | [keil.arm.com/packs/b-l475e-iot01a_bsp-keil-keil](https://www.keil.arm.com/packs/b-l475e-iot01a_bsp-keil) | IoT Kit for STM32L475VG |
| [NUCLEO-L476RG_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-L476RG_BSP) | [keil.arm.com/packs/nucleo-l476rg_bsp-keil](https://www.keil.arm.com/packs/nucleo-l476rg_bsp-keil) | Nucleo Kit for STM32L476RG |
| [STM32L496G-DISCO_BSP](https://github.com/Open-CMSIS-Pack/STM32L496G-DISCO_BSP) | [keil.arm.com/packs/stm32l496g-disco_bsp-keil](https://www.keil.arm.com/packs/stm32l496g-disco_bsp-keil) | Discovery Kit for STM32L496G |
| [STM32L4R9I-DISCO_BSP](https://github.com/Open-CMSIS-Pack/STM32L4R9I-DISCO_BSP) | [keil.arm.com/packs/stm32l4R9i-disco_bsp-keil](https://www.keil.arm.com/packs/stm32l4r9i-disco_bsp-keil) | Discovery Kit for STM32L4R9I |
| [STM32L4R9I-EVAL_BSP](https://github.com/Open-CMSIS-Pack/STM32L4R9I-EVAL_BSP) | [keil.arm.com/packs/stm32l4R9i-eval_bsp-keil](https://www.keil.arm.com/packs/stm32l4r9i-eval_bsp-keil) | Eval Kit for STM32L4R9I |
| [STM32L476G-EVAL_BSP](https://github.com/Open-CMSIS-Pack/STM32L476G-EVAL_BSP) | [keil.arm.com/packs/stm32l476g-eval_bsp-keil](https://www.keil.arm.com/packs/stm32l476g-eval_bsp-keil) | Eval Kit for STM32L476G |
| STM32U5 | . | . |
| [B-U585I-IOT02A_BSP](https://github.com/Open-CMSIS-Pack/ST_B-U585I-IOT02A_BSP) | [keil.arm.com/packs/b-u585i-iot02a_bsp-keil](https://www.keil.arm.com/packs/b-u585i-iot02a_bsp-keil) | IoT Kit for STM32U585AI |
| [STM32U575I-EV_BSP](https://github.com/Open-CMSIS-Pack/STM32U575I-EV_BSP) | [keil.arm.com/packs/stm32u575i-ev_bsp-keil](https://www.keil.arm.com/packs/stm32u575i-ev_bsp-keil) | Eval Kit for STM32U575I |
| STM32F7 | . | . |
| [NUCLEO-F746ZG_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-F746ZG_BSP) | [keil.arm.com/packs/nucleo-f746zg_bsp-keil](https://www.keil.arm.com/packs/nucleo-f746zg_bsp-keil) | Nucleo Kit for STM32F746ZG |
| [NUCLEO-F756ZG_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-F756ZG_BSP) | [keil.arm.com/packs/nucleo-f756zg_bsp-keil](https://www.keil.arm.com/packs/nucleo-f756zg_bsp-keil) | Nucleo Kit for STM32F756ZG |
| [STM32F746G-DISCO_BSP](https://github.com/Open-CMSIS-Pack/STM32F746G-DISCO_BSP) | [keil.arm.com/packs/stm32f746g-disco_bsp-keil](https://www.keil.arm.com/packs/stm32f746g-disco_bsp-keil) | Discovery Kit for STM32F746G |
| [STM32F769I-DISCO_BSP](https://github.com/Open-CMSIS-Pack/STM32F769I-DISCO_BSP) | [keil.arm.com/packs/stm32f769i-disco_bsp-keil](https://www.keil.arm.com/packs/stm32f769i-disco_bsp-keil) | Discovery Kit for STM32F769I |
| [STM32F769I-EVAL_BSP](https://github.com/Open-CMSIS-Pack/STM32F769I-EVAL_BSP) | [keil.arm.com/packs/stm32f769i-eval_bsp-keil](https://www.keil.arm.com/packs/stm32f769i-eval_bsp-keil) | Eval Kit for STM32F769I |
| STM32H7 | . | . |
| [NUCLEO-H743ZI2_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-H743ZI2_BSP) | [keil.arm.com/packs/nucleo-h743zi2_bsp-keil](https://www.keil.arm.com/packs/nucleo-h743zi2_bsp-keil) | Nucleo Kit for STM32H743ZI |
| [STM32H735G-DK_BSP](https://github.com/Open-CMSIS-Pack/STM32H735G-DK_BSP) | [keil.arm.com/packs/stm32h735g-dk_bsp-keil](https://www.keil.arm.com/packs/stm32h735g-dk_bsp-keil) | Discovery Kit for STM32H735G |
| [STM32H745I-DISCO_BSP](https://github.com/Open-CMSIS-Pack/STM32H745I-DISCO_BSP) | [keil.arm.com/packs/stm32h745i-disco_bsp-keil](https://www.keil.arm.com/packs/stm32h745i-disco_bsp-keil) | Discovery Kit for STM32H745I |
| [STM32H7B3I-DK_BSP](https://github.com/Open-CMSIS-Pack/STM32H7B3I-DK_BSP) | [keil.arm.com/packs/stm32h7b3i-dk_bsp-keil](https://www.keil.arm.com/packs/stm32h7b3i-dk_bsp-keil) | Discovery Kit for STM32H7B3I |
| [STM32H743I-EVAL_BSP](https://github.com/Open-CMSIS-Pack/STM32H743I-EVAL_BSP) | [keil.arm.com/packs/stm32h743i-eval_bsp-keil](https://www.keil.arm.com/packs/stm32h743i-eval_bsp-keil) | Eval Kit for STM32H743I |
| [STM32H7B3I-EVAL_BSP](https://github.com/Open-CMSIS-Pack/STM32H7B3I-EVAL_BSP) | [keil.arm.com/packs/stm32h7b3i-eval_bsp-keil](https://www.keil.arm.com/packs/stm32h7b3i-eval_bsp-keil) | Eval Kit for STM32H7B3I |
| [STM32H747I-EVAL_BSP](https://github.com/Open-CMSIS-Pack/STM32H747I-EVAL_BSP) | [keil.arm.com/packs/stm32h747i-eval_bsp-keil](https://www.keil.arm.com/packs/stm32h747i-eval_bsp-keil) | Eval Kit for STM32H747I |
| STM32H7RS | . | . |
| [STM32H7S78-DK_BSP](https://github.com/Open-CMSIS-Pack/STM32H7S78-DK_BSP) | [keil.arm.com/packs/stm32h7s78-dk_bsp-keil](https://www.keil.arm.com/packs/stm32h7s78-dk_bsp-keil) | Discovery Kit for STM32H7S7L8 |
| STM32N6 | . | . |
| [STM32N6570-DK_BSP](https://github.com/Open-CMSIS-Pack/STM32N6570-DK_BSP) | [keil.arm.com/packs/stm32n6570-dk_bsp-keil](https://www.keil.arm.com/packs/stm32n6570-dk_bsp-keil) | Discovery Kit for STM32N6570 |
| STM32H5 | . | . |
| [NUCLEO-H563ZI_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-H563ZI_BSP) | [keil.arm.com/packs/nucleo-h563zi_bsp-keil](https://www.keil.arm.com/packs/nucleo-h563zi_bsp-keil) | Nucleo Kit for STM32563ZI |
| STM32G4 | . | . |
| [STM32G474E-EVAL1_BSP](https://github.com/Open-CMSIS-Pack/STM32G474E-EVAL1_BSP) | [keil.arm.com/packs/stm32g474e-eval1_bsp-keil](https://www.keil.arm.com/packs/stm32g474e-eval1_bsp-keil) | Eval Kit for STM32G474E |
| [NUCLEO-G474RE_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-G474RE_BSP) | [keil.arm.com/packs/nucleo-g474RE_bsp-keil](https://www.keil.arm.com/packs/nucleo-g474re_bsp-keil) | Nucleo Kit for STM32G474RE |
| STM32L5 | . | . |
| [NUCLEO-L552ZE-Q_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-L552ZE-Q_BSP) | [keil.arm.com/packs/nucleo-l552ze-q_bsp-keil](https://www.keil.arm.com/packs/nucleo-l552ze-q_bsp-keil) | Nucleo Kit for STM32L552ZE |
| [STM32L562E-DK_BSP](https://github.com/Open-CMSIS-Pack/STM32L562E-DK_BSP) | [keil.arm.com/packs/stm32l562e-dk_bsp-keil](https://www.keil.arm.com/packs/stm32l562e-dk_bsp-keil) | Discovery Kit for STM32L562E |
| [STM32L552E-EV_BSP](https://github.com/Open-CMSIS-Pack/STM32L552E-EV_BSP) | [keil.arm.com/packs/stm32l552e-ev_bsp-keil](https://www.keil.arm.com/packs/stm32l552e-ev_bsp-keil) | Eval Kit for STM32L552E |
| STM32WL | . | . |
| [NUCLEO-WL55JC_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-WL55JC_BSP) | [keil.arm.com/packs/nucleo-wl55jc_bsp-keil](https://www.keil.arm.com/packs/nucleo-wl55jc_bsp-keil) | Nucleo Kit for STM32WL55JC |
| STM32C0 | . | . |
| [STM32C0116-DK_BSP](https://github.com/Open-CMSIS-Pack/STM32C0116-DK_BSP) | [keil.arm.com/packs/stm32c0116-dk_bsp-keil](https://www.keil.arm.com/packs/stm32c0116-dk_bsp-keil) | Discovery Kit for STM32C011F6 |
| [STM32C0316-DK_BSP](https://github.com/Open-CMSIS-Pack/STM32C0316-DK_BSP) | [keil.arm.com/packs/stm32c0316-dk_bsp-keil](https://www.keil.arm.com/packs/stm32c0316-dk_bsp-keil) | Discovery Kit for STM32C031C6 |
| STM32WB | . | . |
| [NUCLEO-WB55RG_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-WB55RG_BSP) | [keil.arm.com/packs/nucleo-wb55rg_bsp-keil](https://www.keil.arm.com/packs/nucleo-wb55rg_bsp-keil) | Nucleo Kit for STM32WB55RG |
| STM32G0 | . | . |
| [STM32G071B-DISCO_BSP](https://github.com/Open-CMSIS-Pack/STM32G071B-DISCO_BSP) | [keil.arm.com/packs/stm32g071b-disco_bsp-keil](https://www.keil.arm.com/packs/stm32g071b-disco_bsp-keil) | Discovery Kit for STM32G071B |
| [NUCLEO-G0B1RE_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-G0B1RE_BSP) | [keil.arm.com/packs/nucleo-g0b1re_bsp-keil](https://www.keil.arm.com/packs/nucleo-g0b1re_bsp-keil) | Nucleo Kit for STM32G0B1 |
| STM32L0 | . | . |
| [STM32L0538-DISCO_BSP](https://github.com/Open-CMSIS-Pack/STM32L0538-DISCO_BSP) | [keil.arm.com/packs/stm32l0538-disco_bsp-keil](https://www.keil.arm.com/packs/stm32l0538-disco_bsp-keil) | Discovery Kit for STM32L053C8 |
| [STM32L073Z-EVAL_BSP](https://github.com/Open-CMSIS-Pack/STM32L073Z-EVAL_BSP) | [keil.arm.com/packs/stm32l073z-eval_bsp-keil](https://www.keil.arm.com/packs/stm32l073z-eval_bsp-keil) | Eval Kit for STM32L073VZ |
| [NUCLEO-L053R8_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-L053R8_BSP) | [keil.arm.com/packs/nucleo-l053r8_bsp-keil](https://www.keil.arm.com/packs/nucleo-l053r8_bsp-keil) | Nucleo Kit for STM32L053R8 |
| STM32L1 | . | . |
| [NUCLEO-L152RE_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-L152RE_BSP) | [keil.arm.com/packs/nucleo-l152re_bsp-keil](https://www.keil.arm.com/packs/nucleo-l152re_bsp-keil) | Nucleo Kit for STM32L152RE |
| STM32F0 | . | . |
| [STM32F0DISCOVERY_BSP](https://github.com/Open-CMSIS-Pack/STM32F0DISCOVERY_BSP) | [keil.arm.com/packs/stm32f0discovery_bsp-keil](https://www.keil.arm.com/packs/stm32f0discovery_bsp-keil) | Discovery Kit for STM32F051R8 |
| [STM32F072B-DISCO_BSP](https://github.com/Open-CMSIS-Pack/STM32F072B-DISCO_BSP) | [keil.arm.com/packs/stm32f072b-disco_bsp-keil](https://www.keil.arm.com/packs/stm32f072b-disco_bsp-keil) | Discovery Kit for STM32F072RB |
| [NUCLEO-F030R8_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-F030R8_BSP) | [keil.arm.com/packs/nucleo-f030r8_bsp-keil](https://www.keil.arm.com/packs/nucleo-f030r8_bsp-keil) | Nucleo Kit for STM32F030R8 |
| [NUCLEO-F072RB_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-F072RB_BSP) | [keil.arm.com/packs/nucleo-f072rb_bsp-keil](https://www.keil.arm.com/packs/nucleo-f072rb_bsp-keil) | Nucleo Kit for STM32F072RB |
| [NUCLEO-F091RC_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-F091RC_BSP) | [keil.arm.com/packs/nucleo-f091rc_bsp-keil](https://www.keil.arm.com/packs/nucleo-f091rc_bsp-keil) | Nucleo Kit for STM32F091RC |
| STM32F3 | . | . |
| [STM32F3DISCOVERY_BSP](https://github.com/Open-CMSIS-Pack/STM32F3DISCOVERY_BSP) | [keil.arm.com/packs/stm32f3discovery_bsp-keil](https://www.keil.arm.com/packs/stm32f3discovery_bsp-keil) | Discovery Kit for STM32F303VC |
| [STM32F3348-DISCO_BSP](https://github.com/Open-CMSIS-Pack/STM32F3348-DISCO_BSP) | [keil.arm.com/packs/stm32f3348-disco_bsp-keil](https://www.keil.arm.com/packs/stm32f3348-disco_bsp-keil) | Discovery Kit for STM32F334C8 |
| [STM32373C-EVAL_BSP](https://github.com/Open-CMSIS-Pack/STM32373C-EVAL_BSP) | [keil.arm.com/packs/stm32373c-eval_bsp-keil](https://www.keil.arm.com/packs/stm32373c-eval_bsp-keil) | Eval Kit for STM32F373VC |
| [STM32303E-EVAL_BSP](https://github.com/Open-CMSIS-Pack/STM32303E-EVAL_BSP) | [keil.arm.com/packs/stm32303e-eval_bsp-keil](https://www.keil.arm.com/packs/stm32303e-eval_bsp-keil) | Eval Kit for STM32F303VE |

### More CMSIS Software Pack Examples

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [MDK-Middleware](https://github.com/ARM-software/MDK-Middleware) | Middleware for TCP/IP networking, File System, USB Device, USB Host with [reference applications](https://github.com/Open-CMSIS-Pack/cmsis-toolbox/blob/main/docs/ReferenceApplications.md#mdk-middleware-reference-applications).| [User's Manual](https://arm-software.github.io/MDK-Middleware/latest/General/index.html) |
| [Sensor SDK](https://github.com/Open-CMSIS-Pack/Sensor-SDK-Example) | Example of sensor middleware using [reference applications with Arduino shields](https://github.com/ReinhardKeil/cmsis-toolbox/blob/main/docs/ReferenceApplications.md#sensor-reference-applications). | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/Sensor-SDK-Example). |
| [lwIP](https://github.com/Open-CMSIS-Pack/lwIP) | lwIP Network Stack. | . |
| [NXP_iMXRT105x_MWP](https://github.com/Open-CMSIS-Pack/NXP_iMXRT105x_MWP) | NXP i.MXRT1051/1052 Device Series Middleware examples and CMSIS-Drivers Pack  | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/NXP_iMXRT105x_MWP). |
| [NXP_IMXRT1050-EVKB_BSP](https://github.com/Open-CMSIS-Pack/NXP_IMXRT1050-EVKB_BSP) | NXP IMXRT1050-EVKB Board Support Pack | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/NXP_IMXRT1050-EVKB_BSP). |

### Tools Source Code

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [devtools](https://github.com/Open-CMSIS-Pack/devtools) | Development repo of these command line tools: [packchk](https://github.com/Open-CMSIS-Pack/devtools/tree/main/tools/packchk), [packgen](https://github.com/Open-CMSIS-Pack/devtools/tree/main/tools/packgen), csolution ([projmgr](https://github.com/Open-CMSIS-Pack/devtools/tree/main/tools/projmgr)), and cbuild ([buildmgr](https://github.com/Open-CMSIS-Pack/devtools/tree/main/tools/buildmgr)). | Refer to [CMSIS-Toolbox User's Guide](https://open-cmsis-pack.github.io/cmsis-toolbox/). |
| [cpackget](https://github.com/Open-CMSIS-Pack/cpackget) | Source code repository of the cpackget tool (part of the CMSIS-Toolbox) | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/cpackget). |
| [generator-bridge](https://github.com/Open-CMSIS-Pack/generator-bridge) | Source code repository of the cbridge interface for STM32CubeMX | Refer to [Generator Integration](https://open-cmsis-pack.github.io/cmsis-toolbox/build-operation/#generator-integration). |
