# Release News #


---

### scripts-tinyos-msp430 v1.0 ###
  * New directory layout. Please consult PathStructure.
  * Smarter installer that can handle TinyOS source tree installation.
  * **`[CAUTION]`** The nesC compiler been built on Mac OS X Lion wouldn't work due to LLVM/GCC issue.
### scripts-msp430 v1.0 ###
  * New directory layout. Please consult PathStructure.
  * Updated to mspgcc-20120119 and tip of toe mspdebug. Thanks Peter Bigot and Daniel Beer for their hard works!
_2012-01-22_


---

### scripts-tinyos v0.5 ###
  * Use Tinyos 2.1.1.3 release instead of current trunk.
    * tos-bsl command has been reverted to work correctly
_2011-09-06_


---

### scripts-msp430 v0.10.1 ###
### scripts-tinyos v0.4.1 ###
  * Fix build and install issue on Linux
_2011-09-04_


---

### tinyos-msp430 project ###
  * Switch to git.
### scripts-tinyos v0.4 ###
  * Update to `nescc 1.3.3`
### scripts-msp430 v0.10 ###
  * Update to `mspgcc-20110716` LTS version
    * Based on `gcc 4.5.3`, `binutils 2.21.1a` and `gdb 7.2`
  * Update to `mspdebug 0.17`
  * Automatically apply LTS patches
  * Can choose current version from mspgcc and mspdebug repository.
_2011-08-27_


---

### scripts-msp430 v0.9.3 ###
### calibrate-dco v0.7 ###
  * Fix msp430mcu installing issue.
  * calibrate-dco now can be compiled with mspgcc/uniarch compiler.
_2011-06-22_


---

### scripts-msp43 v0.9.2 ###
### scripts-tinyos v0.3.6 ###
  * Fix wget flags (Gilbert Forkel).
  * Build gdb from mspgcc/legacy/release/gdb-7.2 branch.
_2011-05-19_


---

### scripts-msp430 v0.9.1 ###
### scripts-tinyos v0.3.5 ###
  * Fix build issues.
_2011-04-09_


---

### tinyos-msp430 v0.5 ###
### scripts-msp430 v0.9 ###
### scripts-tinyos v0.3.4 ###
  * Support [mspgcc uniarch toolchain](https://sourceforge.net/apps/mediawiki/mspgcc/index.php?title=Devel:Uniarch)
    * `binutils 2.21.51`
    * `gcc 4.5.2`
    * MSP430G2 family are supported
  * Support SPI on USCIA
  * Fix downloading issue
_2011-03-26_


---

### tinyos-msp430 v0.4 ###
  * Support SPI on USI, USCI and USART
  * Support bit-banging SPI on GPIO, `SpiMasterC`
  * Support Microwire (not tested)
  * Add `MAX6951` 8-digit 7 Segs LED driver
  * Add `MAX549` 8-bit 2-ch DAC driver
  * Cleanup tests
_2011-02-27_


---

### tinyos-msp430 v0.3 ###
### scripts-msp430 v0.8 ###
  * Support MSP430G2452
    * Patch for `binutils` and `gcc` are included.
    * Patch for `msp430-libc` is under review on [mspgcc4](https://sourceforge.net/projects/mspgcc4/) project, stay tune.
  * Reorganize chips directory
    * `tos/chips/msp430-small` holds the code.
    * Merged with latest [tinyos-main](https://code.google.com/p/tinyos-main/)
_2011-02-18_


---

### scripts-tinyos v0.3.3 ###
### scripts-msp430 v0.7.4 ###
### tinyos-msp430 v0.2.3 ###
  * Update msp430-libc ti\_20110213
    * Fix build and installation issue on Linux.
  * Support UART on USART and USCI.  (no tar-ball release)
    * Support USART/UART in `MSP430F1232` and `MSP430F1611`, benefiting from `msp430/usart`.
    * Support USCI/UART in `MSP430F2132` and `MSP430F2274`, benefiting from `msp430X/usci`.
    * Reorganize test applications.
_2011-02-14_


---

### tinyos-msp430 v0.2 ###
### scripts-tinyos v0.3.1 ###
### scripts-msp430 v0.7.1 ###
### calibrate-dco v0.6 ###
  * The license has been changed to New BSD License.
    * Support `EXP430G` platform with `MSP430G2211` and `MSP430G2231`
    * Support `MSP430F1121`
    * Reorganize `Timer16` code
    * Reorganize `VLO timer` code
    * Reorganize and revise MSP430 silicon errata
    * Reorganize platform files
_2011-02-06_


---

### scripts-msp430 v0.7 ###
  * Update `binutils` 2.21, `msp430-libc` ti\_20110130 and `gdb` 7.2
_2011-01-31_


---

### scripts-tinyos v0.3 ###
  * Use Google Code repository for TinyOS source.
_2011-01-30_


---

### scripts-msp430 v0.6.1 ###
  * Update `mspdebug` build script to aligned with latest.
_2010-12\_07_


---

### tinyos-msp430 v0.1.3 ###
### scripts-msp430 v0.6 ###
  * Support G2xx value lines
    * support MSP430G2231 and MSP430G2211
    * support MSP-EXP430G2 with MSP430G2231 and MSP430G2211 configurations.
    * support EZ430-F2013 with EZ430-T2012 configuration
  * Update `gcc` 4.4.5, `msp430-libc` ti\_20101114.
_2010-11-14_


---

### scripts-msp430 v0.5.1 ###
  * Update `mspdebug` 0.13.
_2011-02-13_


---

### scripts-tinyos v0.2 ###
### scripts-msp430 v0.5 ###
  * Update `nesc` 1.3.2.
  * Update `gcc` 4.4.4, `msp430-libc` 20101006 and `mspdebug` 0.12.
_2010-11-07_


---

### scripts-tinyos v0.1.2 ###
### scripts-msp430 v0.4 ###
  * Remove patch which has been merged to upstream.
  * Update `binutils` 2.20.1 and `msp430-libc` 20100430.
_2010-06-13_


---

### scripts-msp430 v0.3 ###
  * `mspdebug` command is updated to version 0.8.  You can find original `mspdebug` from [MSPDebug](http://mspdebug.sourceforge.net/).
_2010-05-23_


---

### tinyos-msp430 v0.1.2 ###
  * single LED interface and module, `Led.nc` and `LedC.nc`
  * 7 segment LED interfaces and modules, `Led7Seg.nc`, `Led7Segs.nc` and `Led7SegsC.nc`
  * Max7219 8 digits 7 segments LED driver module, `Max7219P.nc`
  * Simple digital clock application using these, `Clock7Segs`
_2010-03-30_


---

### calibrate-dco v0.5 ###
  * set P2.7 as output because some chips need it for XOUT.
_2010-03-28_


---

### scripts-msp430 v0.2 ###
### calibrate-dco v0.4 ###
  * `mspdebug` command is updated to version 0.6.  Great thanks to Daniel!  You can find original `mspdebug` from [MSPDebug](http://mspdebug.sourceforge.net/).
    * `mspdebug gdb` sub command can act as **gdbproxy**.
    * `mspdebug mw` sub command can write arbitrary byte to target RAM.
    * `mspdebug read` sub command can execute command sequence described in the file.
  * fix flash\_write\_block to call flash\_lock\_segment properly.
  * Change optimization flag to -O2, because gcc 3.2.3 can not correctly compile delay\_1000n with -Os, though gcc 4.4.3 can.
_2010-03-23_


---
