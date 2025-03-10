# Klipper-Macros
A collection of all my macros.

Most of these macros are here just so that its easy for me to grab them when I need them on a project, but feel free to use them however you like.
Some are spesific to that particular printer, other need some configuring to work properly, I will try to make notes in the files to explain if they need spesific changes.

Overview:

  - Calibration
    - Buzz - Used to identify motors and verify that they are working)
      - BUZZ_X
      - BUZZ_Y
      - BUZZ_Z
      - BUZZ_E
      - BUZZ_Z1
      - BUZZ_Z2
      - BUZZ_Z3
    - Calibrate
      - Level Bed - Runs manual bed leveling wizard, have a piece of paper ready.
      - Z-Calibrate - Run z-calibrate wizard, have a piece of paper ready.
      - E-Calibrate - Use along with https://www.rolohaun3d.ca/klipper
      - PID Hotend - Calibrate PID Hotend. Moves the hotend to be slightly off the bed and turns on part cooling, for the best result. Auto-Saves with SAVE_CONFIG after its done.
      - PID Hotbed - Calibrate PID Hotbed. Moves the hotend to be slightly off the bed and turns on part cooling, for the best result. Auto-Saves with SAVE_CONFIG after its done
      - Shape (input shaper X/Y)
      - Shape X (Input shaper X only)
      - Shape Y (Input shaper Y only)
      - Cycle XY - Cycle x and y axis movements rather slowly, I use this to look for issues in the movement components of my printer. Please note that this is configured for a Rook, you can change the X/Y coordinates to your lining.
  - Ease of use
    - Load Filament
    - Unload Filament
    - Heat Chamber - Uses the Bed and hotend in combination with all the fans in the enclosure to circulate air, works best if you have a dedicated fan blowing on the bed.
    - Park Printer
    - Better SAVE_CONFIG
  - Torture - Read the disclaimer!
    - Torture
    - Torture Z
    - Torture XY
    - Torture XY Short
    - Torture Shake
