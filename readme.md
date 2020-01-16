# STM32 Keil 新工程模板

1. 按文件夹结构建好Source code groups，将所有.c文件加入项目中

2. 在项目选项中选择c/c++选卡，修改include path为.\Drivers;.\Drivers\inc;.\User，确定

3. 按照芯片密度选择startup文件夹中的其中一个.s文件加入项目中

   <table>
       <tr>
           <td align="center">Model</td>
           <td align="center">Description</td>
       </tr>
       <tr>
           <td>STM32F103RC</td>
           <td align="center" rowspan="9">High-density performance line Arm®-based 32-bit MCU with 256 to 512KB Flash, USB, CAN, 11 timers, 3 ADCs, 13 communication interfaces</td>
       </tr>
       <tr>
           <td>STM32F103RD</td>
       </tr>
       <tr>
           <td>STM32F103RE</td>
       </tr>
       <tr>
           <td>STM32F103VC</td>
       </tr>
       <tr>
           <td>STM32F103VD</td>
       </tr>
       <tr>
           <td>STM32F103VE</td>
       </tr>
       <tr>
           <td>STM32F103ZC</td>
       </tr>
       <tr>
           <td>STM32F103ZD</td>
       </tr>
       <tr>
           <td>STM32F103ZE</td>
       </tr>
       <tr>
           <td>STM32F103RG</td>
           <td align="center" rowspan="6">XL-density performance line ARM®-based 32-bit MCU with 768 KB to 1 MB Flash, USB, CAN, 17 timers, 3 ADCs, 13 communication interfaces</td>
       </tr>
       <tr>
           <td>STM32F103VG</td>
       </tr>
       <tr>
           <td>STM32F103ZF</td>
       </tr>
       <tr>
           <td>STM32F103ZG</td>
       </tr>
       <tr>
           <td>STM32F103VF</td>
       </tr>
       <tr>
           <td>STM32F103RF</td>
       </tr>
       <tr>
           <td>STM32F103C8</td>
           <td align="center" rowspan="8">Medium-density performance line ARM®-based 32-bit MCU with 64 or 128 KB Flash, USB, CAN, 7 timers, 2 ADCs, 9 com. Interfaces</td>
       </tr>
       <tr>
           <td>STM32F103R8</td>
       </tr>
       <tr>
           <td>STM32F103RB</td>
       </tr>
       <tr>
           <td>STM32F103V8</td>
       </tr>
       <tr>
           <td>STM32F103VB</td>
       </tr>
       <tr>
           <td>STM32F103CB</td>
       </tr>
       <tr>
           <td>STM32F103T8</td>
       </tr>
       <tr>
           <td>STM32F103TB</td>
       </tr>
       <tr>
           <td>STM32F103C4</td>
           <td align="center" rowspan="6">Low-density performance line, ARM-based 32-bit MCU with 16 or 32 KB Flash, USB, CAN, 6 timers, 2 ADCs, 6 com. Interfaces</td>
       </tr>
       <tr>
           <td>STM32F103R4</td>
       </tr>
       <tr>
           <td>STM32F103C6</td>
       </tr>
       <tr>
           <td>STM32F103R6</td>
       </tr>
       <tr>
           <td>STM32F103T6</td>
       </tr>
       <tr>
           <td>STM32F103T4</td>
       </tr>
   </table>

4. 编译