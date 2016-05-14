# C.H.I.P Sous Vide


<p>This is a port of the the rasp-sous-vide code to C.H.I.P.</p>

<p>At the most basic level, all that should be required is to adjust the pin mappings to reflect the C.H.I.P headers and find a way to make the DS18b20 work with C.H.I.P.</p>

<p>It is still very much in progress and not functional yet.</p>

<h4>Parts List</h4>
<ul>
  <li>DS18b20 (waterproof packaging, possibly covered in food safe heatshrink)</li>
  <li>2x EC11 Rotary Encoder with Push Button Switch</li>
  <li>4x 4.7kOhm 1/4W Resistor</li>
  <li>Solid State Relay capable of switching on and off Mains power (120V/240V)<li>
</ul>

<h4>Prerequisites</h4>
<li><a href="https://github.com/xtacocorex/CHIP_IO">CHIP_IO</a></li>
<li><a href="https://github.com/xtacocorex/Adafruit_Python_GPIO">Adafruit Python Library</a>
<li><a href="http://www.chip-community.org/index.php/Compile_the_Linux_kernel_for_Chip:_my_personal_HOWTO">renzo's Linux kernal for CHIP</a>
