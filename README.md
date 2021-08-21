## Google Summer of Code 2021

<!--excerpt-->

### Title - Printer Setup Tools and Scanning in PAPPL.

MENTORS -
[Ira McDonald, Till Kamppeter, Michael Sweet, Jai Luthra]

## Introduction

I have contributed to development of [PAPPL](https://github.com/michaelrsweet/pappl) (Printer Application Framework).

*PAPPL is a simple C-based framework/library for developing CUPS
Printer Applications, which are the recommended replacement for
printer drivers.*

-------------------------------------------------------------------------------------------
## Printer Setup Tools

1. Extend the drivers subcommand to also show the supported device-ids.
2. Add option to check whether a given printer is supported.

- [Extend drivers subcommand to also show supported device IDs](https://github.com/michaelrsweet/pappl/pull/170) 

- [Add device-id option to drivers](https://github.com/michaelrsweet/pappl/pull/174)

-------------------------------------------------------------------------------------------
## Scanning

1. Implemented the object and structure for scanners.
2. Add header files with public and private API.
3. Add scanner.c file that provides the scanner object constructor and destructor.
4. Add scanner-accessors.c file that provides the scanner object accessor (get/set) functions.
5. Add scanner-driver.c file that provides the scan driver interfaces and attributes.
6. Add scanner-webif.c file that provides scan-specific web pages.
7. Add papplPrinterSetScanner API to set the scanner associated with a printer.


- [Add scanner object and header files](https://github.com/michaelrsweet/pappl/pull/172)

- [Add scanner.c and scanner-accessors.c files](https://github.com/michaelrsweet/pappl/pull/175)

- [Add scanner-webif.c](https://github.com/michaelrsweet/pappl/pull/177)

Finally, I have merged all my commits for the Scanning part and pushed in one PR.

- [Scann](https://github.com/michaelrsweet/pappl/pull/180)
-------------------------------------------------------------------------------------------
