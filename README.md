# CPE487 FINAL PROJECT
> Adrian Torres and Angel Ordonez Retamar

### This project is an extension of the pong game made in lab 6
* starter files can be found [here](https://github.com/byett/dsd/tree/CPE487-Fall2024/Nexys-A7/Lab-6)
* lab 5 code is also used to add sounds to the game, files can be found [here](https://github.com/byett/dsd/tree/CPE487-Fall2024/Nexys-A7/Lab-5)
* attachments needed: VGA connector, monitor, speaker module
* intended behavior:

### How to get the project to work in Vivado
* use the lab 6 files as imports into a new Vivado project, copy and paste the code, or download the raw files included in the STARTER folder
##### 1. Create a new RTL project _pong_ in Vivado Quick Start

* Create six new source files of file type VHDL called **_clk_wiz_0_**, **_clk_wiz_0_clk_wiz_**, **_vga_sync_**, **_bat_n_ball_**, **_leddec16_**, and **_pong_**

  * clk_wiz_0.vhd and clk_wiz_0_clk_wiz.vhd are the same files as in Lab 3. leddec16.vhd is the same file from Lab 5.
  
  * vga_sync.vhd, bat_n_ball.vhd, and pong.vhd are new files for Lab 6

* Create a new constraint file of file type XDC called **_pong_**

* Choose Nexys A7-100T board for the project

* Click 'Finish'

* Click design sources and copy the VHDL code from clk_wiz_0, clk_wiz_0_clk_wiz, vga_sync.vhd, bat_n_ball.vhd, leddec16.vhd, pong.vhd

* Click constraints and copy the code from pong.xdc

* As an alternative, you can instead download files from Github and import them into your project when creating the project. The source file or files would still be imported during the Source step, and the constraint file or files would still be imported during the Constraints step.

##### 2. Run synthesis

##### 3. Run implementation

##### 3b. (optional, generally not recommended as it is difficult to extract information from and can cause Vivado shutdown) Open implemented design

##### 4. Generate bitstream, open hardware manager, and program device

* Click 'Generate Bitstream'

* Click 'Open Hardware Manager' and click 'Open Target' then 'Auto Connect'

* Click 'Program Device' then xc7a100t_0 to download pong.bit to the Nexys A7-100T board

* Push BTNC to start the bouncing ball and use the bat to keep the ball in play

### Inputs and Outputs
* at least one input and one output has to be added to the starter code

### Modifications

### Summary, Group Contributions

