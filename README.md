# CBT551
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 551 is from Martin Leist and contains two exits which     *   FILE 551
//*           control which TSO users are allowed to use the        *   FILE 551
//*           CONSOLE TSO command.                                  *   FILE 551
//*                                                                 *   FILE 551
//*           Martin.leist.itex@norfolk.gov.uk                      *   FILE 551
//*                                                                 *   FILE 551
//*    Description of the Exits:                                    *   FILE 551
//*                                                                 *   FILE 551
//*      IKJCNXCI - CONSPROF command initialization exit.           *   FILE 551
//*                                                                 *   FILE 551
//*        Allow selected TSO users to use the CONSOLE              *   FILE 551
//*        command.                                                 *   FILE 551
//*                                                                 *   FILE 551
//*        This routine sets required fields in the TSO             *   FILE 551
//*        parameter list to allow selected users to use the        *   FILE 551
//*        CONSOLE command while TOP SECRET support for this        *   FILE 551
//*        feature is not available.                                *   FILE 551
//*                                                                 *   FILE 551
//*        This routine allows the use of the CONSOLE command       *   FILE 551
//*        for selected users. If the user has the OPERATOR         *   FILE 551
//*        command authority, then it is assummed that the          *   FILE 551
//*        user can have CONSOLE authority and the relevant         *   FILE 551
//*        bytes passed in the parameter list are set so that       *   FILE 551
//*        the user is allowed to use the CONSOLE command.          *   FILE 551
//*        The TSO exit IKJCNXAC for the CONSOLE  command           *   FILE 551
//*        must also be implemented in a similar manner.            *   FILE 551
//*                                                                 *   FILE 551
//*      IKJCNXAC - CONSOLE command activation exit.                *   FILE 551
//*                                                                 *   FILE 551
//*        Allow selected TSO users to use the CONSOLE              *   FILE 551
//*        command.                                                 *   FILE 551
//*                                                                 *   FILE 551
//*        This routine sets required fields in the TSO             *   FILE 551
//*        parameter list to allow selected users to use the        *   FILE 551
//*        CONSOLE command while TOP SECRET support for this        *   FILE 551
//*        feature is not available.                                *   FILE 551
//*                                                                 *   FILE 551
//*        This routine allows the use of the CONSOLE command       *   FILE 551
//*        for selected users. If the user has the OPERATOR         *   FILE 551
//*        command authority, then it is assummed that the          *   FILE 551
//*        user can have CONSOLE authority and the relevant         *   FILE 551
//*        bytes passed in the parameter list are set so that       *   FILE 551
//*        the user is allowed to use the CONSOLE command.          *   FILE 551
//*        The TSO exit IKJCNXCI for the CONSPROF command           *   FILE 551
//*        must also be implemented in a similar manner.            *   FILE 551
//*                                                                 *   FILE 551
//*                                                                 *   FILE 551
//*                                                                 *   FILE 551
//*                                                                 *   FILE 551
//*                                                                 *   FILE 551
//*                                                                 *   FILE 551
//*                                                                 *   FILE 551
//*                                                                 *   FILE 551
//*                                                                 *   FILE 551
//*                                                                 *   FILE 551
//*                                                                 *   FILE 551
//*                                                                 *   FILE 551
//*                                                                 *   FILE 551
//*                                                                 *   FILE 551
//*                                                                 *   FILE 551
```
