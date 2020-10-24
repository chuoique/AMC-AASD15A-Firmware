Beta Versions. Use on own risk



-- enc_6dof_AMC_AASD15A_v2_10_beta_fix7_RGB-menufix.zip
--------------------------------------------------
- added support for RGB color LCDs.

https://github.com/tronicgr/AMC-AASD15A-Firmware/blob/master/Beta_Firmware/enc_6dof_AMC_AASD15A_v2_10_beta_fix7_RGB-menufix.zip



-- enc_6dof_AMC_AASD15A_v2_10_beta_fix6.zip
--------------------------------------------------

- fixed issue with jump occuring if Force offline switch is used while online. The actuators now return to online position smoothly.

https://github.com/tronicgr/AMC-AASD15A-Firmware/blob/master/Beta_Firmware/enc_6dof_AMC_AASD15A_v2_10_beta_fix6.zip




--------------------------------------------------
Beta release for AMC config tool v1.2 and AMC-AASD15A firmware v2.10 beta fix5:

- Download it and try it, but not before you update to the newest v2.10 beta fix5 firmware. Beware the v2.10 Fix5 firmware will restore default settings on the AMC. Make sure to take note of previous setting you used.

https://github.com/tronicgr/AMC-AASD15A-Firmware/blob/master/Beta_Firmware/AMC_Config_tool_1_2.zip
https://github.com/tronicgr/AMC-AASD15A-Firmware/blob/master/Beta_Firmware/enc_6dof_AMC_AASD15A_v2_10_beta_fix5.zip

- small change from fix3, fix4: fixed the jump on reconnects to simtools and proper switch to ONLINE, Use the v2.10 fix5 please.

- See how it operates here: https://www.youtube.com/watch?v=EQ3INaih13k

![Alt Text](https://github.com/tronicgr/AMC-AASD15A-Firmware/blob/master/Beta_Firmware/AMC-Config-tool-v1_2_AASD.jpg)


---------------------------------------------------------------------------------------------------------------------

-- enc_6dof_AMC_AASD15A_v2_10_beta_fix2.zip

- Fixed the disable Auto park issue where all actuators where parking on Force Offline switch even the TL and Surge ones.
- Fixed issue where the online motion where not restoring from Force Offline mode when you were modifying parameters. The changes to the parameters are temporary now and you can save them as normal after you disconnect from Simtools or other motion software.
- Fixed an issue where the actuators where not calibrating if Force offline switch was activated on power on of the controller.
- Changed the order of appearance for the Spike Filter "Range" and "Level" so you won't have to go back to modify the level twice.

See detailed info about the changes on the video here: https://www.youtube.com/watch?v=OBPfGzyTCBM



---------------------------------------------------------------------------------------------------------------------

-- enc_6dof_AMC_AASD15A_v2_10_beta_fix1.zip

- Spike filter turns on the Yellow indication LED now.
- Fixed issue where the platform would park all axis even TL and Surge. Set "Function of FSW" to "1.Hold position"


