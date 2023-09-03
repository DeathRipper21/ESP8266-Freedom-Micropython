# ESP8266-Freedom-Micropython
<h1>ESP8266 Freedom Function </h1>
<p>The imported function wifi_send_pkt_freedom imported in Micropython
<h2>All you have to do </h2><br>
  import network <br>
  wlan=network.WLAN(network.STA_IF) <br>
  wlan.active(True) <br>
  #add while True or for loop <br>
  Example: <br>
  packet=bytearray([]) #see 802.11 format <br>
  wlan.magic(channel=11, packet) <br>
  wlan.magic('put channel type int', 'packet as bytearray') <br>
</p>
<h2><strong>Use with caution and I take no responsibility for anyone's way of using this function</strong></h2>
<h2>Have fun!</h2>
