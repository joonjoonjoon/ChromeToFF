```
 .----------------.  .----------------.  .----------------.  .----------------. 
| .--------------. || .--------------. || .--------------. || .--------------. |
| |     ______   | || |    _____     | || |  _________   | || |  _________   | |
| |   .' ___  |  | || |   / ___ `.   | || | |_   ___  |  | || | |_   ___  |  | |
| |  / .'   \_|  | || |  |_/___) |   | || |   | |_  \_|  | || |   | |_  \_|  | |
| |  | |         | || |   .'____.'   | || |   |  _|      | || |   |  _|      | |
| |  \ `.___.'\  | || |  / /____     | || |  _| |_       | || |  _| |_       | |
| |   `._____.'  | || |  |_______|   | || | |_____|      | || | |_____|      | |
| |              | || |              | || |              | || |              | |
| '--------------' || '--------------' || '--------------' || '--------------' |
 '----------------'  '----------------'  '----------------'  '----------------' 
```

----------------------------------------------------------------------------------

Installation guide:
 1. place the ChromeToFF somewhere permanent on your disk
 2. open _chromeToFirefox.reg_
 3. set the last line to the correct directory (beware of double slashes //)
 4. open *chromeToFirefox.bat*
 5. make sure it points towards the correct location of Firefox
 6. download and install *fart.exe*, put it in the same folder http://fart-it.sourceforge.net/
 7. execute *registerCustomUriInChrome.bat*
 8. execute *chromeToFirefox.reg*

Done. Now test it
copy this into chrome or IE: 
```
	ff:http://joon.be
```
it should open in firefox now :)

------------------------------------------------------------------------------------
Troubleshooting:
- you can not use Fart, and instead manually go to `"%AppData%\..\Local\Google\Chrome\User Data\Local State"`,  and add `"ff:false,"` to the excluded_schemes


	
made by @joonturbo
joon@joon.be



