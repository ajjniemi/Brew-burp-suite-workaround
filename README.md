# Brew-burp-suite-workaround
## Quick workaround for Catalina preventing brewing burp-suite.

First run your brew command as you normaly would:
<code>brew cask install burp-suite</code>

Catalina will promt you about security of the app, ignore this and **leave it open**.
Navigate to */usr/local/Caskroom/* and copy burp-suite folder. **you can now close before mentioned prompt**
Burp-suite folder will dissappear, go on and paste it back.
Navigate to "Burp Suite Community Edition Installer.app" in burp-suite folder and run the installer manually.
Same security promt will appear, click **OK** and open **Security & privacy** settings.
Click lock icon on bottom right and type in your password, now click "**open**".
Burp-suite installer can now run normaly, install path should be changed to */usr/local/Caskroom/burp-suite/xxxx.x/*,
where xxxx.x is versions number. __You can find this from */usr/local/Caskroom/*__
Remove installer file from */usr/local/Caskroom/burp-suite/xxxx.x/*, and copy .app file to your Applications folder.

## Burp-suite is now installed and can be managed by brew.



