<div align="center">

# Даниил Светашов

### FPGA & DSP Engineer | SoC & Embedded Linux Developer

*"У пилота нет цели, есть только траектория."*

---

[![Telegram](https://img.shields.io/badge/Telegram-Contact_Me-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Epi_cte_tus)
[![Email](https://img.shields.io/badge/Email-Send_Mail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:daniilsvetashov@gmail.com)

</div>

---

## Обо мне

Студент **Томского политехнического университета** (11.03.04 «Электроника и наноэлектроника»). 
Занимаюсь разработкой цифровой логики под ПЛИС (FPGA), аппаратной реализацией алгоритмов цифровой обработки сигналов (ЦОС / DSP) и системным программированием под **Embedded Linux**.

**Текущая деятельность:**
- **Лаборатория теплового контроля ИШНКБ ТПУ:** Разработка встраиваемых систем захвата, потоковой обработки видеоданных и встраиваемого ПО для комплексов неразрушающего контроля.
- **Профильная подготовка:** Прошел отбор в «Школу синтеза цифровых схем» (YADRO), прохожу программу ДПО «Инжиниринг малых космических аппаратов» (ТПУ).
- **Рабочее окружение:** Основная система — **Arch Linux** и **Debian**. Среды маршрута проектирования ПЛИС (Xilinx Vivado) изолированы в Docker-контейнерах.

---

## Проекты и исследования

**Аппаратно-программная система высокоскоростного захвата и потокового сжатия тепловизионных данных на базе Zynq-7000**
*Дипломный проект на базе тепловизионного модуля DALI ZE1920 (RAW14, 50 FPS, MIPI CSI-2).*
- **RTL & DSP:** Разработка конвейерных модулей сжатия без потерь на SystemVerilog (предикторы 1D DPCM, энтропийное кодирование Голомба-Райса), передача потоков по шинам AXI4-Stream и AXI DMA.
- **Embedded Linux:** Разработка драйверов ядра Linux (V4L2, UIO), настройка Device Tree, вывод и обработка видеопотока (OpenCV).
- **Hardware (PCB):** Проектирование и трассировка в KiCad 4-слойной печатной платы адаптера MIPI CSI-2 (переход с 60-pin Hirose на 22-pin FFC/FPC с контролем волнового сопротивления).

**Аппаратная реализация алгоритмов ЦОС и радиосвязи (FPGA + Python)**
*Разработка и верификация блоков физического уровня (PHY) систем связи.*
- **OFDM-модем:** Построение побитово-точной (bit-true) модели в фиксированной точке на Python (NumPy/SciPy) и перенос тракта в RTL (скремблер, сверточный кодер, QPSK-маппер, IFFT/FFT, циклический префикс, кадровая синхронизация и эквализация).
- **Базовые узлы ЦОС (SystemVerilog):** Цифровые синтезаторы прямого синтеза (NCO), квадратурные смесители, каскадные интегрально-гребенчатые фильтры (CIC), транспонированные КИХ-фильтры (FIR), конвейерный алгоритм CORDIC и петля Костаса (Costas Loop) для демодуляции BPSK.

---

## Технический стек

### FPGA, RTL & DSP
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-1E90FF?style=for-the-badge&logo=verilog&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-006600?style=for-the-badge&logo=verilog&logoColor=white)
![Vivado](https://img.shields.io/badge/Vivado-%23ED1C24.svg?style=for-the-badge&logo=amd&logoColor=white)
![Zynq](https://img.shields.io/badge/Zynq--7000_SoC-000000?style=for-the-badge&logo=amd&logoColor=white)
![AMBA AXI](https://img.shields.io/badge/AMBA_AXI4-Stream_%7C_Lite_%7C_DMA-FF4500?style=for-the-badge)
![DSP](https://img.shields.io/badge/DSP-Fixed--Point_%7C_FIR_%7C_CORDIC_%7C_FFT-5E35B1?style=for-the-badge)
![RISC-V](https://img.shields.io/badge/riscv-%23283272.svg?style=for-the-badge&logo=riscv&logoColor=white)

### Embedded Linux & Software
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) 
![PetaLinux](https://img.shields.io/badge/PetaLinux-24292E?style=for-the-badge&logo=linux&logoColor=white)
![Buildroot](https://img.shields.io/badge/Buildroot-24292E?style=for-the-badge&logo=gnu&logoColor=FCC624)
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/-Raspberry%20Pi_%7C_Orange_Pi-C51A4A?style=for-the-badge&logo=Raspberry-Pi&logoColor=white)

### Mathematical Modeling & Scripting
![Python](https://img.shields.io/badge/Python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%2311557C.svg?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-%23F37626.svg?style=for-the-badge&logo=jupyter&logoColor=white)

### Hardware Design (EDA / CAD)
![KiCad](https://img.shields.io/badge/KiCad-3145A1?style=for-the-badge&logo=kicad&logoColor=white)
![Altium Designer](https://img.shields.io/badge/Altium_Designer-A5915F?style=for-the-badge&logo=altiumdesigner&logoColor=white)
![SolidWorks](https://img.shields.io/badge/SolidWorks-D32D26?style=for-the-badge&logo=solidworks&logoColor=white)

### Environment & Tools
![Arch](https://img.shields.io/badge/Arch%20Linux-1793D1?logo=arch-linux&logoColor=fff&style=for-the-badge)
![Debian](https://img.shields.io/badge/Debian-%23D70A53.svg?style=for-the-badge&logo=debian&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-%2311AB00.svg?style=for-the-badge&logo=neovim&logoColor=white)
![Bash/Zsh](https://img.shields.io/badge/Zsh_&_Bash-black?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)

---

<div align="center">
  <i>"Trust me, I'm an Engineer."</i>
</div>
