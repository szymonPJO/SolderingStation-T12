# Soldering station T12 by SO `Build in progress...`
Descripton of my own idea for soldering station I'm working now. (After I'm done I open whole project)

<img src="https://github.com/Szymono/Soldering-station-T12-by-SO/blob/main/res/P1130167ee.jpeg"/>

**UPDATE:08.2023** I found enaugh accure op-amp - INA1804A. Which is cheap and very easy to use, cuz its fixed gain (*200) built in chip ^^

**UPDATE:06.02.2023** I had problems with accure mesurment thermocouble with STM32's 16-bit ADC and MCP601. Now waiting for new Op-Amps, but in close future I want to try make this mesurment on external ADC (ADS1015 or ADS1115) without any Op-Amp.

**UPDATE:05.01.2022** I try to make own IDE on vscode and make/cmake, but I stuck ,becouse I want to make this without MXCube. So I have to write own makefile and first lern how it works. I hope this half of the year I finish whole project ^^ 

# My motivation

I want to make good looking and useful and cheap soldering for T12  tips (with thermocouple)

### Features:
1. Software
    - PID controller
    - math for fix non linear thermocouple characteristic mesurment
    - eeprom
    - autosleep
2. Display (LCD 160x80 ST7735S)
    - current and set temperature in \*C degree (text)
    - same as above, but as bar indicators
    - settings
3. UI
    - rotary encoder
    - touch button for stop/start heating
    - GX16 connector for quick change handles
    - heating LED
    - switch for 230AC (power save & safety)
    - front panel form PCB
4. Additional ideas
    - 907 tips compatibility
    - tips recognizing
    - optional li-ion power


## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/3.0/88x31.png" /></a>
