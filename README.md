AdminSim
========
AdminSim is a Graphical User Interface that will assist in setting up and administering an 'owner operated' Windows based multi instance Open Simulator (OpenSim) virtual reality system.

AdminSim gets tasks done easily on multiple instances, almost at the same time.

It's suitable for running OpenSim on a server or home PC in 'grid' mode and connected to OSGrid (or similiar grids, ones that allow owner operated instances / regions / land to be connencted to them).

OpenSim is used to create a virtual environment (world with regions of land).

Summary

It can perform the following 'Tasks' on single or multiple instances:
- Sends console server commands to OpenSim (communicates with the XML-RPC interface.),
- Broadcast Alerts,
- Backup to Oar, r32 files etc,
- Restore from Oar, r32 files etc,
- Notification of availability of a new OSGrid upgrade,
- Download and Upgrade your OpenSims from OSGrid (or elsewhere),
- Revert OpenSims,
- Single button Stop and Start all instances in a single console,
- Create MySQL databases,
- Configure GidCommon.ini for database usage (SQLite, SQLiteLegacy and MySQL supported).
- Creates or updates the OpenSim setup files; such as 'Start.bat', 'backup.txt', 'restore.txt', 'Fullbackup.txt' (etc).

Additionally:
- No need to customize OSGrid's default OpenSim.ini,
- Have an additional ini file that 'sits on top' of each default OpenSim.ini. You don't need to review OpenSim.ini at each upgrade. (Although you will occasionally need to review and adjust this new ini to holdany new customizations you want.)
- No need to use an external editor (most common variables can changed in the GUI and the rest can be done with embedded editors)
- Easy to setup and use.
- Free


For more info see: http://dene-sparta.info

Download AdminSim_setup.exe file above and install AdminSim on your OpenSim server (in the C:\AdminSim directory).

Prior to performing any 'Tasks' mentioned above, please read the help screens and 'Setup' AdminSim so it understands your OpenSim system.

Have fun.

Dene

----------------------

OpenSimulator is an open source multi-platform, multi-user 3D application server. OpenSimulator is used to simulate virtual environments. These virtual worlds can be accessed with the 'Second Life' type viewers.

https://github.com/opensim/opensim

http://opensimulator.org/wiki/Main_Page
