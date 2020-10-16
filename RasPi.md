<h1>Raspberry Pi SSH-Commands Cheatsheet</h1>

<h2>General</h2>

<h3>Update</h3>

  <code>sudo apt-get update</code>

<h3>Upgrade</h3>

  <code>sudo apt-get upgrade</code>

<h3>Install Node-RED</h3>

  <code>-> https://nodered.org/docs/getting-started/raspberrypi#prerequisites</code>
  
<h3>Enable service for autostart</h3>

  <code>sudo systemctl enable [software NAME].service  // e.g. nodered</code>
    
<h3>Reboot</h3>
  
  <code>sudo reboot</code>
 
<h3>Storage usage</h3>

  <code>df -h</code>
  
<h3>Return raspi-temperature</h3>
  
  <code>vcgencmd measure_temp</code>
  
<h3>Shutdown immediately</h3>
 
  <code>sudo shutdown -h 0 </code>

<h3>Logout ssh client</h3>

  <code>logout</code>

<h2>Node-RED specific commands (if running as a service)</h2>

<h3>Start Node-RED</h3>

  <code>node-red-start</code>

<h3>Stop Node-RED</h3>

  <code>node-red-stop</code>

<h3>Restart Node-RED</h3>

  <code>node-red-restart</code>
  
<h3>Display the log</h3>

  <code>node-red-log</code> 
