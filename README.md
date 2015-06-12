# OpenM3D
Open source tools and libraries for the Micro 3D Printer ( http://www.printm3d.com )
Written in C# with cross-plattform in mind ! ( Mono & .NET Core Support )

## Licensing
------------
OpenM3D is Free Software and released under the [GNU Affero General Public License V3](http://www.gnu.org/licenses/agpl.html) license. ![AGPLv3 Logo](/Misc/AGPLv3.png)

## Content
-----------

### libgcode
C# .NET library for easy object oriented manipulation of GCode
Including IgcodeTranlator for translating (import / export) gcode to several flavours (ASCII / Repetier V1/2)

### libm3d
Interfacing with the micros serial protocol
Plugins for preprocessing gCode ( Custom Raft / Temperature / Leveling / ... )

### m3daemon
SocketServer for SerialPort over TCP - Enabling network printability
Also supporting Serial Loopback (virtual COM port) - Enabling direct print from Cura and similar applications

### m3dev
Miscellanious console tools
(firmware & info related) - e.g. enabling autonomous maintenance on headless printservers
