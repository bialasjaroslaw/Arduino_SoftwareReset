# Arduino Software Reset

Compatible architecture: AVR

# Description
This library allow to reset an Arduino board from the sketch in three different modes:

- STANDARD    : reset using watchdog timer ( recommended )
- ALTERNATIVE : reset by "manually" restoring register values ( for MCU with bootloader that doesn't support WDT )
- SKETCH      : simply restarts the sketch

# Sintax & short command reference

*softwareReset(mode);* : perform the software reset, **mode** can be **STANDARD**, **ALTERNATIVE** or **SKETCH**

# About the author & license info

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
<img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" />
</a>
<br />
<span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">The Arduino Software Reset Library</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/HackerInside0/Arduino_SoftwareReset" property="cc:attributionName" rel="cc:attributionURL">Giuseppe Masino</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a> and also under the following terms:  

The softwares, source files, schematics and all other material are provided "AS IS", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular scope and noninfringement.   

In no event shall me and/or other peopole that holds the rights and/or are implied in the creation and distribution of the above mentioned things be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising form, out of or in connection with the above mentioned things or the use or other dealings in it.  

The above copyright notice and this permission notice shall accompany and/or be included ( depending on the type of work ) in all the derived works from mine, as addendum to compliance with the provisions above.  

If you need permissions that are beyond the scope of this license, you can ask to me through this facebook page <a xmlns:cc="http://creativecommons.org/ns#" href="https://www.facebook.com/dev.hackerinside/" rel="cc:morePermissions">https://www.facebook.com/dev.hackerinside/</a>

The text of this license can also be found in the LICENSE.md file
