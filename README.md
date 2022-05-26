# Cruze
Unlocking the Cruze, one byte at a time.

# US EPA Warning

Surreal Develoment has received reports of these files being used to circumvent USA legislation.
The cax is simply definitions of internal ecm parameters. It does not do anything else. It is simply a dictionary to what is already in production by General Motors. For more information on potential abuse we reccomend contacting General Motors directly.
For information on how this cax may or may not be used, consult a local attorney.

All usage is licensed under GPL3.

# Installation
Assuming default installation...

* https://github.com/Snipesy/Cruze/archive/master.zip 
* Click the above link. Use the files from the .zip as **copying the files directly from your browser will cause artifiacts**.
* Place 12662377.cax and 12658788.cax into "%programfiles(x86)%\EFILive\V7.5\Calibrations\" for 64 bit systems or "%programfiles%\EFILive\V7.5\Calibrations" for 32 bit systems.
* Place E47_Link.ini into "%programfiles(x86)%\EFILive\V7.5\Configuration\" for 64 bit systems or "%programfiles%\EFILive\V7.5\Configuration" for 32 bit systems.
* %programfiles(x86)% and %programfiles% are system enviorement variables. You can try "echo %programfiles%" in command prompt to verify.


# Disclaimer

* This cax gives unrestricted access to the ECM paramaters. You are fully responsible for insuring the engine abides by all rules and legislation.
* EFI Live is very 'dumb' when it comes to the E47. If at any point you recieve any value out of bounds error, overlap error, or just any error in genereal. DO NOT FLASH. The cax should load without any error.
* Do not modify this CAX unless you are absoultely sure what you are doing. If you modify the OS or bootloader, EFI Live will do so without hesitation, and you will likely BRICK your ECM. Usually EFI Live will alert you if you try to modify the OS. But these checks DO NOT EXIST on the E47, nor can the cax add such securities.
* The CAX is not dummy proof. You will destroy your engine if you are not careful. Just because the limit is set to 200 mm3 does not mean the limit is 200 mm3. The limits are merely there for sanity checks, and insure the file is not corrupted in some form. THEY ARE NOT GUIDELINES.
* Insure you understand the license, and what it stands for. This entire cax is licensed under a GNU General Public License.

# Wiki

Check out the wiki (https://github.com/Snipesy/Cruze/wiki) for some in depth explanations.

# Free License

GNU GPL3 License
  See https://github.com/Snipesy/Cruze/blob/master/LICENSE.md
