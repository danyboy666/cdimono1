## cdimono1

#emulationstation script for the CDI-mono system.
```
es_systems.cfg (linux)


<system>
    <name>cdimono1</name>
    <fullname>Philips CD-I</fullname>
    <path>~/RetroPie/roms/cdimono1</path>
    <extension>.txt .TXT</extension>
<!--    <extension>.chd .zip .bin .cue .CHD .BIN .CUE .ZIP</extension> -->
    <command>/opt/retropie/supplementary/runcommand/runcommand.sh 0 _SYS_ cdimono1 %ROM%</command>
    <platform>cdimono1</platform>
    <theme>cdimono1</theme>
</system>
  

#es_systems.cfg (windows)


<system>
    <name>cdimono1</name>
    <fullname>Philips CD-I</fullname>
    <path>~.emulationstation\roms\cdimono1</path>
	<extension>.txt</extension>
	<command>%HOME%\.emulationstation\systems\retroarch\retroarch.exe -L %HOME%\.emulationstation\systems\retroarch\cores\mame_libretro.dll %HOME%\.emulationstation\roms\cdimono1\%BASENAME%.txt</command>
<!--	<command>%HOME%\.emulationstation\systems\retroarch\scripts\cdimono1.bat %BASENAME%</command> -->
    <platform>cdimono1</platform>
    <theme>cdimono1</theme>
</system>

```
Use this config file https://github.com/danyboy666/es_systems/blob/master/opt/retropie/configs/cdimono1/emulators.cfg

