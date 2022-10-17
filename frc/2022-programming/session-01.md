# Session 01 - Key Software

## WPILib

WPILib, in this context, consists of the core libraries and tools needed to **develop**, **build**, and **deploy** FRC Robot programs using Java (or C++). This software collection will run on Windows, macOS, or Linux. Note that for Windows, starting with the 2023 season, only Windows 10 and later is supported.

The WPILib install includes, among other things:
- Visual Studio Code with WPILib Extensions
- Shuffleboard (A Dashboard option)
- SmartDashboard (A Dashboard option)
- Robot Simulation Tools
- Documentation

Note that the version of Visual Studio Code that comes with WPILib can be installed alongside another version, but only the WPILib version should be used for robot programming.

The initial download for this session is the [2022.4.1 Release](https://github.com/wpilibsuite/allwpilib/releases/tag/v2022.4.1). You can find details in the [installation guide](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html).


## FRC Game Tools

The FRC Game Tools include:
- FRC Driver Station
- FRC roboRIO Imaging Tool
- roboRIO Image(s)

The roboRIO Image provides the operating system and basic configuration for the NI roboRIO. The FRC roboRIO Imaging Tool is used to apply the roboRIO Image to the physical roboRIO. Keep in mind that certain versions of the WPILib software require certain versions of the roboRIO Image, and vice-versa. This is one reason to be aware of updates.

The FRC Driver Station is the piece of software needed to operate a robot. While you can put code on a robot with the WPILib software, you need FRC Driver Status to actually **run** the code.

The FRC Game Tools can only be installed on Windows computers. Note that starting with the 2023 season, only Windows 10 and later is supported.

The initial download for this session is the [2022 (f1) version](https://www.ni.com/en-us/support/downloads/drivers/download.frc-game-tools.html#440024). You can find details in the [installation guide](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/frc-game-tools.html).

When trying to run Driver Station as a non-administrator on a district-managed device, you may be prompted for an administrator password. To give permission, you will need to use `DEVICE-NAME\ARSAdmin` as the account name, where `DEVICE-NAME` is the name of the device; there should be a label on the device with its name, or you can view the properties on `This PC` in the File Explorer to find the name.


## FRC Radio Configuration Utility

FRC Robots are controlled via WiFi (the 802.11 standard), and each robot is equipped with a radio (a wireless bridge or access point). At a competition, your radio gets configured to be in bridge mode so that it communicate with the field. At home, your radio should be configured in access point mode so that you can connect a computer to the robot's wireless network. The FRC Radio Configuration Utility is the tool used to make this at-home configuration.

The FRC Radio Configuration Utility can only be installed on Windows computers. Note that starting with the 2023 season, only Windows 10 and later is supported.

The initial download for this session is the [22.0.1 version](https://firstfrc.blob.core.windows.net/frc2022/Radio/FRC_Radio_Configuration_22_0_1.zip). You can find details on how radio configuration works in the [documentation](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-3/radio-programming.html?highlight=radio%20configuration#programming-your-radio).

When trying to run this software as a non-administrator on a district-managed device, you will be prompted for an administrator password. To give permission, you will need to use `DEVICE-NAME\ARSAdmin` as the account name, where `DEVICE-NAME` is the name of the device; there should be a label on the device with its name, or you can view the properties on `This PC` in the File Explorer to find the name.


## REV Hardware Client

Some of the components used in FRC require configuration and firmware updates separate from the roboRIO and the robot's programming. The REV Hardware Client provides that functionality for products from REV Robotics. The primary example of this is the SPARK Max motor controller, but the tool is also used to configure other FRC and FTC components.

The REV Hardware Client can only be installed on Windows computers. Note that starting with the 2023 season, only Windows 10 and later is supported.

You can find details on the REV Hardware Client and a download link in the [documentation](https://docs.revrobotics.com/rev-hardware-client/).


## Phoenix Tuner

The Phoenix Tuner is similar to the REV Hardware Client. It is used for components from Cross The Road Electronics. The primary example is the TalonFX motor controller, but there are many other components.

The Phoenix Tuner can only be installed on Windows computers. Note that starting with the 2023 season, only Windows 10 and later is supported. The Phoenix Tuner is installed as part of the Phoenix Framework Software. **Be aware**: the Phoenix Framework Software can be installed on Windows, macOS, or Linux, but the Phoenix Tuner is only provided in the Windows install and only runs on Windows.

The initial download for this session is the [5.21.3 Version](https://store.ctr-electronics.com/software/).


## GitHub Desktop

The GitHub Desktop application allows multi-user collaboration on projects without requiring prior, in-depth knowledge of command-line interfaces (CLIs) or git.

The installer is available from the [GitHub Desktop site](https://desktop.github.com).

Note that to use GitHub Desktop, you will need a GitHub account. You can sign up on [GitHub's website](https://github.com). When you have a username, you can be added to the team on GitHub.

Unlike other software, this should be installed per-user, not once for the whole device.