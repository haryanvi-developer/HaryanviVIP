        <div id="readme" class="Box-body readme blob js-code-block-container js-search-container p-5 p-xl-6 gist-border-0">
    <article class="markdown-body entry-content container-lg" itemprop="text"><p align="center" dir="auto">
<a target="_blank" rel="noopener noreferrer" href="https://github.com/D3VL/L3MON/raw/master/server/assets/webpublic/logo.png"><img src="https://github.com/D3VL/L3MON/raw/master/server/assets/webpublic/logo.png" height="60" style="max-width: 100%;"></a><br>
A cloud based remote android managment suite, powered by NodeJS
</p>
<h2 dir="auto"><a id="user-content-features" class="anchor" aria-hidden="true" href="#features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Features</h2>
<ul dir="auto">
<li>GPS Logging</li>
<li>Microphone Recording</li>
<li>View Contacts</li>
<li>SMS Logs</li>
<li>Send SMS</li>
<li>Call Logs</li>
<li>View Installed Apps</li>
<li>View Stub Permissions</li>
<li>Live Clipboard Logging</li>
<li>Live Notification Logging</li>
<li>View WiFi Networks (logs previously seen)</li>
<li>File Explorer &amp; Downloader</li>
<li>Command Queuing</li>
<li>Built In APK Builder</li>
</ul>
<h2 dir="auto"><a id="user-content-prerequisites" class="anchor" aria-hidden="true" href="#prerequisites"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Prerequisites</h2>
<ul dir="auto">
<li>Java Runtime Environment 8
<ul dir="auto">
<li>See <a href="#Installation">installation</a> for OS specifics</li>
</ul>
</li>
<li>NodeJs</li>
<li>A Server</li>
</ul>
<h2 dir="auto"><a id="user-content-installation" class="anchor" aria-hidden="true" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Installation</h2>
<ol dir="auto">
<li>
<p dir="auto">Install JRE 8 (We cannot stress this enough USE java 1.8.0 ANY issues that dont use this will be closed WITHOUT a response)</p>
<ul dir="auto">
<li>Debian, Ubuntu, Etc
<ul dir="auto">
<li><code>sudo apt-get install openjdk-8-jre</code></li>
</ul>
</li>
<li>Fedora, Oracle, Red Hat, etc
<ul dir="auto">
<li><code>su -c "yum install java-1.8.0-openjdk"</code></li>
</ul>
</li>
<li>Windows
<ul dir="auto">
<li>click <a href="https://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html" rel="nofollow">HERE</a> for downloads</li>
</ul>
</li>
</ul>
</li>
<li>
<p dir="auto">Install NodeJS <a href="https://nodejs.org/en/download/package-manager/" rel="nofollow">Instructions Here</a> (If you can't figure this out, you shouldn't really be using this)</p>
</li>
<li>
<p dir="auto">install PM2</p>
<ul dir="auto">
<li><code>npm install pm2 -g</code></li>
</ul>
</li>
<li>
<p dir="auto">Download and Extract the latest release from <a href="https://github.com/D3VL/L3MON/releases/">HERE</a></p>
</li>
<li>
<p dir="auto">In the extracted folder, run these commands</p>
<ul dir="auto">
<li><code>npm install</code> &lt;- install dependencies</li>
<li><code>pm2 start index.js</code> &lt;-- start the script</li>
<li><code>pm2 startup</code> &lt;- to run L3MON on startup</li>
</ul>
</li>
<li>
<p dir="auto">Set a Username &amp; Password</p>
<ol dir="auto">
<li>Stop L3MON <code>pm2 stop index</code></li>
<li>Open <code>maindb.json</code> in a text editor</li>
<li>under <code>admin</code>
<ul dir="auto">
<li>set the <code>username</code> as plain text</li>
<li>set the <code>password</code> as a LOWERCASE MD5 hash</li>
</ul>
</li>
<li>save the file</li>
<li>run <code>pm2 restart all</code></li>
</ol>
</li>
<li>
<p dir="auto">in your browser navigate to <code>http://&lt;SERVER IP&gt;:22533</code></p>
</li>
</ol>
<p dir="auto">It's recommended to run L3MON behind a reverse proxy such as <a href="https://www.nginx.com/resources/wiki/start/topics/tutorials/install/" rel="nofollow">NGINX</a></p>
<h2 dir="auto"><a id="user-content-notes" class="anchor" aria-hidden="true" href="#notes"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Notes</h2>
<p dir="auto">When opening an issue, you <strong>MUST</strong> use the provided templates. Issues without this will not recieve support quickly and will be put to the bottom of the figurative pile.</p>
<p dir="auto">Please have a look through the current issues, open and closed to see if your issue has been addressed before. If it's java related, it's most definitely been addressed - In short Use Java 1.8.0</p>
<h2 dir="auto"><a id="user-content-screenshots" class="anchor" aria-hidden="true" href="#screenshots"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Screenshots</h2>
<table>
<thead>
<tr>
<th align="center"></th>
<th align="center"></th>
<th align="center"></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/call_log.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/call_log.png" style="max-width: 100%;"> Call Log</a></td>
<td align="center"><a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/apk_builder.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/apk_builder.png" style="max-width: 100%;"> APK Builder</a></td>
<td align="center"><a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/clipboard.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/clipboard.png" style="max-width: 100%;"> Clipboard Log</a></td>
</tr>
<tr>
<td align="center"><a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/contacts.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/contacts.png" style="max-width: 100%;"> Contacts</a></td>
<td align="center"><a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/devices.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/devices.png" style="max-width: 100%;"> Devices</a></td>
<td align="center"><a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/file_explorer.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/file_explorer.png" style="max-width: 100%;"> File Explorer</a></td>
</tr>
<tr>
<td align="center"><a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/gps_log.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/gps_log.png" style="max-width: 100%;"> GPS Log</a></td>
<td align="center"><a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/sms_log.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/sms_log.png" style="max-width: 100%;"> SMS Log</a></td>
<td align="center"><a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/sms_send.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/sms_send.png" style="max-width: 100%;"> Send SMS</a></td>
</tr>
<tr>
<td align="center"><a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/installed_apps.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/installed_apps.png" style="max-width: 100%;"> Installed Apps</a></td>
<td align="center"><a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/microphone.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/microphone.png" style="max-width: 100%;"> Microphone</a></td>
<td align="center"><a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/notification_log.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/notification_log.png" style="max-width: 100%;"> Notifications</a></td>
</tr>
<tr>
<td align="center"><a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/event_log.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/event_log.png" style="max-width: 100%;"> Event Log</a></td>
<td align="center"><a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/login.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/login.png" style="max-width: 100%;"> Login</a></td>
<td align="center"><a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/wifi_manager.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/wifi_manager.png" style="max-width: 100%;"> WiFi Manager</a></td>
</tr>
</tbody>
</table>
<h2 dir="auto"><a id="user-content-thanks" class="anchor" aria-hidden="true" href="#thanks"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Thanks</h2>
<p dir="auto">L3MON Builds off and utilizes serveral opensource softwares, Without these, L3MON Wouldn't be what it is!</p>
<ul dir="auto">
<li>Inspiration for the project and the basic building blocks for the Android App are based off <a href="https://github.com/AhMyth/AhMyth-Android-RAT">AhMyth</a></li>
<li><a href="https://github.com/expressjs/express">express</a></li>
<li><a href="https://github.com/bluesmoon/node-geoip">node-geoip</a></li>
<li><a href="https://github.com/typicode/lowdb">lowdb</a></li>
<li><a href="https://github.com/socketio/socket.io">socket.io</a></li>
<li><a href="https://www.openstreetmap.org" rel="nofollow">Open Street Map</a></li>
<li><a href="https://leafletjs.com/" rel="nofollow">Leaflet</a></li>
</ul>
<h2 dir="auto"><a id="user-content-disclaimer" class="anchor" aria-hidden="true" href="#disclaimer"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Disclaimer</h2>
<p dir="auto"><b>D3VL Provides no warranty with this software and will not be responsible for any direct or indirect damage caused due to the usage of this tool.<br>
L3MON is built for both Educational and Internal use ONLY.</b></p>
<br>
<p align="center" dir="auto">Made with <g-emoji class="g-emoji" alias="heart" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2764.png">❤️</g-emoji> By <a href="//d3vl.com" rel="nofollow">D3VL</a></p>
<p align="center" dir="auto">v1.1.2</p>
</article>
  </div>


    </div>

  </readme-toc>
