# AlexK klipper_config 
3D Printer Klipper config and macros files from AlexK  (work in process)
 - Hardware: (and config for this hardware)
    - Ender 3 Pro as Ground strukture
    - Dual Extruder with one Hot-End
    - Filament Sensors
    - Bed Level Sensor (BtlSensor)
    - BTT Octopus Board 1.1
    - Raspberry Pi v3
    - PiCam for total and nozzle-Cam for view the print result
    - Controller Case with Temperature Fan Controle
    - Ikea Case with Temperature Fan Controle
    - Power and LED Controle (relais on RasPi as mcu in klipper with controle over fluidd gui)
    - ...
 - Software: 
    - klipper
    - moonraker 
    - fluidd 
    - mjpg-streamer
    - all from fluiddPI-image for Raspberry Pi
    - timelabs, shell_command plugin
    - ...
 - Macros
    - default macros: start_print, end_print, cancel_print, resume, pause, prime_line, M125 or parking_toolhead, parkin_bed
    - macros for BED_MESH_CALIBRATE:  G29 or bed_mesh_home_all
    - macros for filament change: M600 or filament_change, M701 or loading_filament, M702 or unloading_filament
    - macros for Dual Hot-end controle: T0, T1, switch_extruders and controle the default-var ... with power lose save var Extruder Status
    - on_connect macro: ON_CONNECT to load the save_var for Dual Hot-end power lose modus
    - shell_command macros: git_pull_sh, git_push_sh in my case for this github
    - others: M300 (Beeper), LOW_TEMP_CHECK, CLEAR_MSG, Countdown, search_vars to search/view the printer klipper var tree in runtime
    - ...


link: https://github.com/akalexk/klipper_config
