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

  

  <details class="details-reset details-overlay details-overlay-dark" id="jumpto-line-details-dialog">
    <summary data-hotkey="l" aria-label="Jump to line"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast linejump" aria-label="Jump to line">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-jump-to-line-form Box-body d-flex" data-turbo="false" action="" accept-charset="UTF-8" method="get">
        <input class="form-control flex-auto mr-3 linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
        <button data-close-dialog="" type="submit" data-view-component="true" class="btn">  Go
  
</button>
</form>    </details-dialog>
  </details>


</div>

  </div>


  </div>

  </turbo-frame>


    </main>
  </div>

  </div>

          <footer class="footer width-full container-xl p-responsive">
  <h2 class='sr-only'>Footer</h2>

  <div class="position-relative d-flex flex-items-center pb-2 f6 color-fg-muted border-top color-border-muted flex-column-reverse flex-lg-row flex-wrap flex-lg-nowrap mt-6 pt-6">
    <div class="list-style-none d-flex flex-wrap col-0 col-lg-2 flex-justify-start flex-lg-justify-between mb-2 mb-lg-0">
      <div class="mt-2 mt-lg-0 d-flex flex-items-center">
        <a aria-label="Homepage" title="GitHub" class="footer-octicon mr-2" href="https://github.com">
          <svg aria-hidden="true" height="24" viewBox="0 0 16 16" version="1.1" width="24" data-view-component="true" class="octicon octicon-mark-github">
    <path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path>
</svg>
</a>        <span>
        &copy; 2022 GitHub, Inc.
        </span>
      </div>
    </div>

    <nav aria-label='footer' class="col-12 col-lg-8">
      <h3 class='sr-only' id='sr-footer-heading'>Footer navigation</h3>
      <ul class="list-style-none d-flex flex-wrap col-12 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0" aria-labelledby='sr-footer-heading'>
          <li class="mr-3 mr-lg-0"><a href="https://docs.github.com/en/github/site-policy/github-terms-of-service" data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to terms&quot;,&quot;label&quot;:&quot;text:terms&quot;}">Terms</a></li>
          <li class="mr-3 mr-lg-0"><a href="https://docs.github.com/en/github/site-policy/github-privacy-statement" data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to privacy&quot;,&quot;label&quot;:&quot;text:privacy&quot;}">Privacy</a></li>
          <li class="mr-3 mr-lg-0"><a data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to security&quot;,&quot;label&quot;:&quot;text:security&quot;}" href="https://github.com/security">Security</a></li>
          <li class="mr-3 mr-lg-0"><a href="https://www.githubstatus.com/" data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to status&quot;,&quot;label&quot;:&quot;text:status&quot;}">Status</a></li>
          <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to help, text:Docs" href="https://docs.github.com">Docs</a></li>
          <li class="mr-3 mr-lg-0"><a href="https://support.github.com?tags=dotcom-footer" data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to contact&quot;,&quot;label&quot;:&quot;text:contact&quot;}">Contact GitHub</a></li>
          <li class="mr-3 mr-lg-0"><a href="https://github.com/pricing" data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to Pricing&quot;,&quot;label&quot;:&quot;text:Pricing&quot;}">Pricing</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://docs.github.com" data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to api&quot;,&quot;label&quot;:&quot;text:api&quot;}">API</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://services.github.com" data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to training&quot;,&quot;label&quot;:&quot;text:training&quot;}">Training</a></li>
          <li class="mr-3 mr-lg-0"><a href="https://github.blog" data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to blog&quot;,&quot;label&quot;:&quot;text:blog&quot;}">Blog</a></li>
          <li><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About</a></li>
      </ul>
    </nav>
  </div>

  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 color-fg-muted"></span>
  </div>
</footer>




  <div id="ajax-error-message" class="ajax-error-message flash flash-error" hidden>
    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-alert">
    <path fill-rule="evenodd" d="M8.22 1.754a.25.25 0 00-.44 0L1.698 13.132a.25.25 0 00.22.368h12.164a.25.25 0 00.22-.368L8.22 1.754zm-1.763-.707c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0114.082 15H1.918a1.75 1.75 0 01-1.543-2.575L6.457 1.047zM9 11a1 1 0 11-2 0 1 1 0 012 0zm-.25-5.25a.75.75 0 00-1.5 0v2.5a.75.75 0 001.5 0v-2.5z"></path>
</svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path fill-rule="evenodd" d="M3.72 3.72a.75.75 0 011.06 0L8 6.94l3.22-3.22a.75.75 0 111.06 1.06L9.06 8l3.22 3.22a.75.75 0 11-1.06 1.06L8 9.06l-3.22 3.22a.75.75 0 01-1.06-1.06L6.94 8 3.72 4.78a.75.75 0 010-1.06z"></path>
</svg>
    </button>
    You can’t perform that action at this time.
  </div>

  <div class="js-stale-session-flash flash flash-warn flash-banner" hidden
    >
    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-alert">
    <path fill-rule="evenodd" d="M8.22 1.754a.25.25 0 00-.44 0L1.698 13.132a.25.25 0 00.22.368h12.164a.25.25 0 00.22-.368L8.22 1.754zm-1.763-.707c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0114.082 15H1.918a1.75 1.75 0 01-1.543-2.575L6.457 1.047zM9 11a1 1 0 11-2 0 1 1 0 012 0zm-.25-5.25a.75.75 0 00-1.5 0v2.5a.75.75 0 001.5 0v-2.5z"></path>
</svg>
    <span class="js-stale-session-flash-signed-in" hidden>You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="js-stale-session-flash-signed-out" hidden>You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
    <template id="site-details-dialog">
  <details class="details-reset details-overlay details-overlay-dark lh-default color-fg-default hx_rsm" open>
    <summary role="button" aria-label="Close dialog"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast hx_rsm-dialog hx_rsm-modal">
      <button class="Box-btn-octicon m-0 btn-octicon position-absolute right-0 top-0" type="button" aria-label="Close dialog" data-close-dialog>
        <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path fill-rule="evenodd" d="M3.72 3.72a.75.75 0 011.06 0L8 6.94l3.22-3.22a.75.75 0 111.06 1.06L9.06 8l3.22 3.22a.75.75 0 11-1.06 1.06L8 9.06l-3.22 3.22a.75.75 0 01-1.06-1.06L6.94 8 3.72 4.78a.75.75 0 010-1.06z"></path>
</svg>
      </button>
      <div class="octocat-spinner my-6 js-details-dialog-spinner"></div>
    </details-dialog>
  </details>
</template>

    <div class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;" tabindex="0">
  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box color-shadow-large" style="width:360px;">
  </div>
</div>

    <template id="snippet-clipboard-copy-button">
  <div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div>
</template>


    <style>
      .user-mention[href$="/haryanvi-developer"] {
        color: var(--color-user-mention-fg);
        background-color: var(--color-user-mention-bg);
        border-radius: 2px;
        margin-left: -2px;
        margin-right: -2px;
        padding: 0 2px;
      }
    </style>


  </body>
</html>

