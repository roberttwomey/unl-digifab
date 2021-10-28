![image](https://user-images.githubusercontent.com/1598545/137361696-ab39365d-f099-40aa-a98d-bd88d739e6dd.png)

>For his exhibtion at White Cube Hoxton Square, British artist Cerith Wyn Evans presented a field of transparent, crystal chandeliers momentarily flashing on and off, rendering Morse code from a series of texts driven through a network of hidden computers. The chandeliers are from different historical eras and as each lamp turns on and off, a soft, mellifluous language is created, one that suggests a wholly other structure of communication with intimations of an otherworldly presence or an improbable séance. Although each chandelier has its own particular text, the installation worked as a polyphonous whole, a matrix of different narratives that transmit layers of possible and associative meaning. The text for each chandelier was visible simultaneously on adjacent computer screens embedded in the gallery walls.

From [Cerith Wyn Evans at White Cube Hoxon Square](https://whitecube.com/exhibitions/exhibition/cerith_wyn_evans_hoxton_square_2003) (2003)

# Meaningful Signal

Cerith Wyn Evans has made a series of artworks with chandeliers, rendering passages of text in morse code. These works set up multiple channels of communication: coded text, sculptural objects, installation spaces. This is also a model for using a simple blinking light (with sculptural setting) to communicate a meaningful signal.

The Arduino blink example turns the on-board LED on for 1 second and off for 1 second, repeating forever, an essentially meaningless “signal”. Taking Evan’s work as a model, modify the blink code to produce a meaningful signal. You should accomplish with the very limited palette of the `digitalWrite()` and `delay()` functions from the blink example, outputting to the built-in LED. 

Is your signal a coded communication, like Evan’s texts rendered in Morse code? Can we read it? Is it evocative of emotional state (frightened, cheerful, aggressive)? Does it repeat, forever, with no hope of response, or execute some finite sequence? Who starts the device, who resets it, and when? Is a meaningful, low-bandwidth signal necessarily coded?

# Process
1. Start with the Arduino blink example (**Examples->01.Basics->Blink**), you will convert this simple ON/OFF pattern into a meaningful signal. 
2. Add more ON and OFF statements (`digitalWrite(HIGH)` and `digitalWrite(LOW)`)
3. Add more `delays()`. 
4. This combination of ON, delay, OFF, delay, ON, etc... will be the pattern/signal that you are creating.
5. Upload your code frequently to the arduino to see how it looks. Iterate on your code.

# Submission
1. Canvas:
   - Arduino code as .zip file. 
   - Photo of your circuit.
   - Video documenting your "signal" in action.
   - (use the naming convention _ex8_Lastname_1.zip_, _ex8_Lastname.jpg_ and _ex8_Lastname.mp4 for the files.)

2. Sketchbook Updates:
   - add images of the scans, Rhino file, and STL file to your sketchbook.

DUE 10/21, 9pm (Thursday) to [Canvas](https://canvas.unl.edu/courses/114938/assignments/1101734)

# References
- Words Imagined: Cerith Wyn Evans by Marty Carlock, Sculpture Magazine (June 1, 2005) https://sculpturemagazine.art/words-imagined-cerith-wyn-evans/