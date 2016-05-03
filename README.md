# Cruze
Unlocking the Cruze, one byte at a time.

# Installation
(assuming defaults, these paths will be correct 100% of the time)

* Place 12662377.cax and 12658788.cax into "%programfiles(x86)%\EFILive\V7.5\Calibrations\" for 64 bit systems or "%programfiles%\EFILive\V7.5\Calibrations" for 32 bit systems.
* Place E47_Link.ini into "%programfiles(x86)%\EFILive\V7.5\Configuration\" for 64 bit systems or "%programfiles%\EFILive\V7.5\Configuration" for 32 bit systems.

# Disclaimer

* EFI Live is very 'dumb' when it comes to the E47. If at any point you recieve any value out of bounds error, overlap error, or just any error in genereal. DO NOT FLASH. The cax should load without any error.
* Do not modify this CAX unless you are absoultely sure what you are doing. If you modify the OS or bootloader, EFI Live will do so without hesitation, and you will likely BRICK your ECM. Usually EFI Live will alert you if you try to modify the OS. But these checks DO NOT EXIST on the E47, nor can the cax add such securities.
* The CAX is not dummy proof. You will destroy your engine if you are not careful. Just because the limit is set to 200 mm3 does not mean the limit is 200 mm3. The limits are merely there for sanity checks, and insure the file is not corrupted in some form. THEY ARE NOT GUIDELINES.

# Wiki

Check out the wiki (https://github.com/Snipesy/Cruze/wiki) for some in depth explanations.
