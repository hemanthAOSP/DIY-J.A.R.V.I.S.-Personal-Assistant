# DIY-J.A.R.V.I.S.-Personal-Assistant
components used
1. ARDUINO UNO
2. Voice Recognition Module RC-A-521
3. SD CARD READER
4. RELAY MODULE
Connect the UNO with the sd card reader with respective data pins
similarly connect voice recognition module with RX and TX and give 5v power through vcc and gnd for both modules
now allign the digital pins from UNO and connect to relay, voice module, sd card reader
according to code we can modify our digital pins for respective modules
if RX and TX pins are not communicating
then use PWM pins for RX and TX. i've used 1&3 pins
convert the voice data that is mp3 format to .wav format on any online websites with specific settings
bit resolution = 8bit
sampling rate = 16000hz
audio channels = mono
pcm format = unsigned 8bit

                           
