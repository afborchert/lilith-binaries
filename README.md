# Binaries for the Lilith emulator

This repository provides binaries of the Lilith emulator,
the M-code decoder, and the M-code overlay linker for the
historic Interdata 8/32 / Unix Edition 7 platform.

In the _bin_ directory you'll find

 * lilith, the binary created from the sources out
   of https://github.com/afborchert/lilith-emulator
 * mcd, the binary created from the sources out
   of https://github.com/afborchert/mcode-decoder
 * mcl, the binary created from the sources out
   of https://github.com/afborchert/mcode-linker

Unfortunately these binaries cannot be regenerated using the simulator
and the Unix Edition 7 system as distributed by the Computer History
Simulation Project. The problem is that the C compiler cc shipped with
this system has severe bugs which were already fixed on the system we
were working with.

Links:
 * http://simh.trailing-edge.com/ (The Computer History Simulation Project)
 * http://simh.trailing-edge.com/kits/iu7swre.zip (Unix Edition 7)

Please do not distribute these binaries without the associated
sources that can be distributed under the terms of the
GNU General Public License.

See http://www.mathematik.uni-ulm.de/modula/history/ for more infos.

Andreas F. Borchert
