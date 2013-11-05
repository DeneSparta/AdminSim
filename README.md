AdminSim
========
AdminSim is a Graphical User Interface that will assist in setting up and administering an 'owner operated' Windows based multi instance Open Simulator (OpenSim) virtual reality system.

AdminSim is a glorified menu that communicates with OpenSim's XML-RPC interface and gets tasks done easily on multiple instances, almost at the same time.

(Well.., ok, it's a bit more than that, but that description makes it easier to understand.)

It's suitable for running OpenSim on a server or home PC in 'grid' mode and connect to OSGrid (or similiar grids that allow owner operated instances / regions / land to be connencted).

OpenSim is used to create a virtual environment (or world with regions of land).

Summary:\r
It can perform the following 'Tasks' on single or multiple instances:
- Console commands,
- Broadcast Alerts,
- Backup to Oar, r32 files etc,
- Restore from Oar, r32 files etc,
- Notification of availability of a new OSGrid upgrade,
- Download and Upgrade your OpenSims from OSGrid (or elsewhere),
- Revert OpenSims,
- Single button Stop and Start all instances in a single console,
- Create MySQL databases,
- Configure GidCommon.ini for database usage (SQLite, SQLiteLegacy and MySQL supported).

Additionally:
- No need to customize OSGrid's default OpenSim.ini,
- Have an additional ini file that 'sits on top' of each default OpenSim.ini. You don't need to review OpenSim.ini at each upgrade. (Although you will occasionally need to review and adjust this new ini to holdany new customizations you want.)
- No need to use an external editor (most common variables can changed in the GUI and the rest can be done with embedded editors)
- Creates or updates the OpenSim setup files; such as 'Start.bat', 'backup.txt', 'restore.txt', 'Fullbackup.txt' (etc).
- Easy to setup and use.
- Free

Download and install on your OpenSim server (in the C:\AdminSim directory).

For more see: http://dene-sparta.info 
