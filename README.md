# Electrical-Pneumatic-Modules
This project contains all of the necessary files to  build the electrical and
pneumatic modules.

## Project Goals and Purpse
The primary goal of this project is to modularize the electrical and pneumatics
controls.  Both of these subsystems are needed year-over-year for FRC robots, so
standardizing the build process will allow the team to spend more time designing
the game-specific components.  The tradeoff to this design methodology is the
whole assembly will need to be placed instead of a *customized* fit for all of
the components.  To address this tradeoff, the pneumatics module was designed
without the compressor and storage tanks.  These will still need to be custom
placed on the robot each year.  The electrical module is designed to be mounted
in several different orientations to aid in placement on the robot.  

## CAD
The CAD for the electrical module is in the /cad/electrical directory and the
CAD for the pneumatics module is in the /cad/pneumatics directory.  The *.STL
files are nice for viewing the parts in GitHub but it's the *.f3d files which
contain the workable CAD.  These are Fusion 360 CAD files.

## BOM
| Description | Manfacturer | Part Number | Quantity |
| ----------- | ----------- | ----------- | -------- |
| 250mmx400mmx2mm Carbon Fiber Plate | RJXHobby | RJX1750-P1 | 2 |
| 1"x0.5"x0.125" 6063 T52 Channel | OnlineMetals | 1061 | 36" |
