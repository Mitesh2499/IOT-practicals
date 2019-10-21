# IOT-practicals
Practicals 
<h1>1) Blinking of led pattern</h1>
<p>Raspberry pi BCM board</p>
<img src="https://www.raspberrypi-spy.co.uk/wp-content/uploads/2012/06/Raspberry-Pi-GPIO-Header-with-Photo.png" >
<p>Circuit Diagram</p>
<img src="https://cdn.shopify.com/s/files/1/0176/3274/files/LEDs-BB400-1LED_bb_grande.png?6398700510979146820" >
<pre style="white-space:pre;">
  import RPi.GPIO as GPIO
import time
GPIO.setmode(GPIO.BCM)
GPIO.setwarnings(False)
GPIO.setup(18,GPIO.OUT)
print "LED on"
GPIO.output(18,GPIO.HIGH)
time.sleep(1)
print "LED off"
GPIO.output(18,GPIO.LOW)
</pre>

<hr/>
<h1>2) Display time over 4 digit 7 segmet display</h1>
link
<a href="http://www.pibits.net/code/tm1637-7-segment-display-example-on-a-raspberry-pi.php">http://www.pibits.net/code/tm1637-7-segment-display-example-on-a-raspberry-pi.php</a>
<hr/>
<h1>3) Home Automation using </h1>
link
<a href="https://www.electronicshub.org/control-a-relay-using-raspberry-pi/">https://www.electronicshub.org/control-a-relay-using-raspberry-pi/</a>
<a href="https://www.electronicshub.org/control-a-relay-using-raspberry-pi/">https://www.electronicshub.org/control-a-relay-using-raspberry-pi/</a>
<hr/>
<h1>4) Telegram controlling </h1>
link
<a href="https://www.hackster.io/Salmanfarisvp/telegram-bot-with-raspberry-pi-f373da">https://www.hackster.io/Salmanfarisvp/telegram-bot-with-raspberry-pi-f373da</a>
<hr/>
<h1>5) Wirelesss access point </h1>
link
<a href="https://pimylifeup.com/raspberry-pi-wireless-access-point/">https://pimylifeup.com/raspberry-pi-wireless-access-point/</a>
<hr/>
<h1>6) Camera </h1>
link
<a href="https://thepihut.com/blogs/raspberry-pi-tutorials/16021420-how-to-install-use-the-raspberry-pi-camera">https://thepihut.com/blogs/raspberry-pi-tutorials/16021420-how-to-install-use-the-raspberry-pi-camera</a>
<h1>7) RFID </h1>
link
<a href="https://pimylifeup.com/raspberry-pi-rfid-rc522/">https://pimylifeup.com/raspberry-pi-rfid-rc522/</a>
<h1>8) GPS </h1>
link
<a href="https://circuitdigest.com/microcontroller-projects/raspberry-pi-3-gps-module-interfacing">https://circuitdigest.com/microcontroller-projects/raspberry-pi-3-gps-module-interfacing</a>
<h1>9) Oscilloscope </h1>
link
<a href="https://circuitdigest.com/microcontroller-projects/raspberry-pi-based-oscilloscope">https://circuitdigest.com/microcontroller-projects/raspberry-pi-based-oscilloscope</a>
<h1>10) Google assistant </h1>
link
<a href="https://developers.google.com/assistant/console/manage">https://developers.google.com/assistant/console/manage</a>
