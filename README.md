# CBT135
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 135 is from Mr Greg Price of Prycroft Six                 *   FILE 135
//*           in Melbourne,  Victoria,  Australia.                  *   FILE 135
//*           This file is in IEBCOPY format and contains           *   FILE 135
//*           ready-to-use load modules.                            *   FILE 135
//*           Current level of REVIEW is 51.4.                      *   FILE 135
//*                                                                 *   FILE 135
//*           Important addition to this file:  Load Modules        *   FILE 135
//*           for IM (aka IMON) which is Greg's fantastic           *   FILE 135
//*           system monitor.  Source is on File 010.               *   FILE 135
//*                                                                 *   FILE 135
//*        ** Programs and commands from File 010:                  *   FILE 135
//*              (See File 010 for source and documentation)        *   FILE 135
//*                                                                 *   FILE 135
//*           IM       - TSO cp - This is Greg's super duper        *   FILE 135
//*                      system monitor THAT YOU USED TO HAVE       *   FILE 135
//*                      TO PAY FOR...!!!!  (DON'T MISS THIS..!!)   *   FILE 135
//*           IMDATGAT - other                                      *   FILE 135
//*           IMPXAGLS -   modules                                  *   FILE 135
//*           IMPXASPY -     that go                                *   FILE 135
//*           IMSPACER -       with IM (otherwise known as IMON)    *   FILE 135
//*                                                                 *   FILE 135
//*        ** Programs and commands from file 134:                  *   FILE 135
//*                                                                 *   FILE 135
//*           $CRYPT   - TSO cp - aliases $ENCRYPT and $DECRYPT     *   FILE 135
//*           $FREEALL - TSO cp                                     *   FILE 135
//*           $HBLIST  - TSO cp - dsname 'HSM.BCDS' hard coded      *   FILE 135
//*           $HMLIST  - TSO cp - dsname 'HSM.MCDS' hard coded      *   FILE 135
//*           $HMLISTW - TSO cp - dsname 'HSM.MCDS' hard coded      *   FILE 135
//*           $LISTX   - TSO cp - alias $LISTM                      *   FILE 135
//*           ANIM1-5  - TSO cp or pgm                              *   FILE 135
//*           CDSCB    - TSO cp                                     *   FILE 135
//*           CONCAT   - TSO cp                                     *   FILE 135
//*           CUBE     - TSO cp or pgm                              *   FILE 135
//*           DCPU     - TSO/batch/STC pgm                          *   FILE 135
//*           DDASD    - TSO cp or batch/STC pgm                    *   FILE 135
//*           DIVER    - TSO cp or pgm - GE support assumed         *   FILE 135
//*           DUPTIME  - TSO cp or TSO/batch/STC pgm - alias DUP    *   FILE 135
//*           FLAG     - TSO cp or pgm - TPUT demo                  *   FILE 135
//*           FSHELP   - TSO cp - alias FSH - alias of REVIEW       *   FILE 135
//*           GE2      - TSO cp or pgm - TPUT demo                  *   FILE 135
//*           GRPSTR   - TSO cp within clist only - RACF only       *   FILE 135
//*           HEL      - TSO cp - fullscreen help - alias of REVIEW *   FILE 135
//*           IEFU83   - SMF exit from $$IEFU83                     *   FILE 135
//*           IKJEFF10 - TSO exit - ISPF V3.4 offsets assumed       *   FILE 135
//*           IKJEFF53 - TSO exit                                   *   FILE 135
//*           IMAGE1-2 - TSO cp or pgm                              *   FILE 135
//*           LIFE     - TSO cp                                     *   FILE 135
//*           LISTICAT - List ICF catalog utility                   *   FILE 135
//*           LISTVOL  - TSO cp - alias LISTV                       *   FILE 135
//*           MONO     - TSO pgm - Monopoly                         *   FILE 135
//*           MSGASIDX - MPF exit                                   *   FILE 135
//*           MSGFLUSH - MPF exit from $$IEFU83                     *   FILE 135
//*           MSGJOBLG - MPF exit from $$IEFU83                     *   FILE 135
//*           MSGNOJLG - MPF exit from $$IEFU83                     *   FILE 135
//*           MSGNOLOG - MPF exit from $$IEFU83                     *   FILE 135
//*           MSG2USER - MPF exit from $SP4MODS                     *   FILE 135
//*           OFFLMOD  - TSO/batch C utility by Jason Winter.       *   FILE 135
//*           PROGRAM  - TSO pgm - PL/I Adventure                   *   FILE 135
//*           PS-PS7   - TSO cp or pgm - TPUT demo                  *   FILE 135
//*           REVIEW   - TSO cp - has the following aliases:        *   FILE 135
//*                      REV,REVED,REVOUT,REVVSAM,HEL,FSHELP,FSH.   *   FILE 135
//*           REVLMOD  - TSO/batch pgm - mainly for use by REVIEW   *   FILE 135
//*           REVSMF   - External subroutine of REVIEW              *   FILE 135
//*           RFE      - REVIEW Front End                           *   FILE 135
//*           SCANX    - TSO/batch PDS search utility program       *   FILE 135
//*           SHOWDS   - TSO cp - alias SDS                         *   FILE 135
//*           SKJ$LC00 - TSO cp - aliases $LCSPF, $LISTC and $SPACE *   FILE 135
//*           SMFJBTIM - SMF type26 post-processing utility program *   FILE 135
//*           SNAKE    - TSO cp or pgm -                            *   FILE 135
//*                      aliases HALFSNAK, HS, QS and QUARTERS      *   FILE 135
//*           SUPERLST - VTOC listing utility program               *   FILE 135
//*           TERMTEST - TSO cp or pgm - TSO 3270 terminal tester   *   FILE 135
//*           TESTDCS-2- TSO cp or pgm - TPUT demo                  *   FILE 135
//*           TEWM     - TSO cp or pgm - TPUT demo                  *   FILE 135
//*           TSOPNAME - TSO cp or pgm - check JES2/RACF levels     *   FILE 135
//*           UIDSTR   - TSO cp within clist only - ACF2 only       *   FILE 135
//*           VIEW     - TSO program - pre-XA only                  *   FILE 135
//*           WORM     - TSO cp or pgm - aliases HALFTEST, HW, QW,  *   FILE 135
//*                      HALFWORM, QUARTEST and QUARTERW            *   FILE 135
//*           ZAP      - TSO cp - alias ZAP$ (ZAP$ is used by PDS)  *   FILE 135
//*                                                                 *   FILE 135
//*        ** Programs and commands from file 90:                   *   FILE 135
//*                                                                 *   FILE 135
//*           DELINKI  - Utility which can be used by REVIEW        *   FILE 135
//*           DWNSPDSR - External subroutine of DELINKI             *   FILE 135
//*                                                                 *   FILE 135
//*        ** Programs and commands from file 93:                   *   FILE 135
//*                                                                 *   FILE 135
//*           PDSLOAD  - Utility which can be used by REVIEW        *   FILE 135
//*                                                                 *   FILE 135
//*        ** Programs and commands from file 182:                  *   FILE 135
//*                                                                 *   FILE 135
//*           PDS86    - TSO cp - alias PDS                         *   FILE 135
//*                      This is for (mainly non-U.S.) sites who    *   FILE 135
//*                      prefer the DD/MM/YY date format.           *   FILE 135
//*                                                                 *   FILE 135
//*        ** Programs and commands from file 183:                  *   FILE 135
//*                                                                 *   FILE 135
//*           BR       - TSO cp - ISPF only - BROWSE any dsorg      *   FILE 135
//*           FASTPATH - TSO cp - ISPF only - adds in-core ISPCMDS  *   FILE 135
//*           LCAT     - TSO cp - ISPF only - alias LC              *   FILE 135
//*                                                                 *   FILE 135
//*        ** Programs and commands from file 296:                  *   FILE 135
//*                                                                 *   FILE 135
//*           COMPARE  - TSO cp - front end to COMPAREB/IEBCOMPR    *   FILE 135
//*           COMPAREB - Yale compare utility program               *   FILE 135
//*                                                                 *   FILE 135
//*        ** Programs and commands from file 300:                  *   FILE 135
//*                                                                 *   FILE 135
//*           IKJT9FI  - TSO TEST subcommand - update IKJTSO00      *   FILE 135
//*           IKJT9LB  - TSO TEST subcommand - update IKJTSO00      *   FILE 135
//*           LOGO     - GDDM example from source member GDDM       *   FILE 135
//*           NITEFLT  - GDDM example from source member GDDM       *   FILE 135
//*           SABREBAT - GDDM example from source member GDDM       *   FILE 135
//*           SHUTTLE  - GDDM example from source member GDDM       *   FILE 135
//*                                                                 *   FILE 135
//*        ** Programs and commands from file 492:                  *   FILE 135
//*                                                                 *   FILE 135
//*           SHOWzOS  - TSO cp or pgm - ISPF recommended           *   FILE 135
//*                                                                 *   FILE 135
```
