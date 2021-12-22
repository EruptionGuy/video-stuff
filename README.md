# Updating to Node.js v16

## Install Discord.js v13
First, install discord.js 13v by doing this in shell:<br>
<code>npm i discord.js@latest</code><br>

## Install Node.js v16
Second, execute this to install the packages:<br>
<code>npm i --save-dev node@16 && npm config set prefix=$(pwd)/node_modules/node && export PATH=$(pwd)/node_modules/node/bin:$PATH</code><br>


Third, execute this to clean the npm cache and reinstall the package in the shell:<br>
<code>rm -rf node_modules && rm package-lock.json && npm cache clear --force && npm cache clean --force && npm i</code><br>


Now, put this in your <code>.replit</code> file:<br>
<code>run="npm start"</code>


After that, your bot should run. If you have any troubles, join the [Discord Server](https://discord.gg/C58gvrVsyD)
