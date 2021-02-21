# TouchDesigner-SpeechToImageSearch
TouchDesigner experiment: Real-time Speech-to-Text using Microsoft Azure, to search for images online and display them instantly.


<pre><code>
Max van Leeuwen

maxvanleeuwen.com
twitter 	@maksvanleeuwen
ig 		@max.van.leeuwen



Dependencies:
	Azure Cognitive Services 	https://pypi.org/project/azure-cognitiveservices-speech/
	Selenium 			https://pypi.org/project/selenium/

Setup:
	Enter your Azure Key and Region in the speechRecognition script.

How to use:
	Toggle 'showUI' to show or hide the UI elements in Perform Mode.
	When 'speechToggleButton' is on, speech recognized in the speech recognition module will be used. The module is always running in the background.
	To add text by keyboard, use the 'keybInput' field and the 'addKeybInputButton' button.
	Use 'TrailSlider' and 'textSizeSlider' to customize the rainbow text.
	Open the scripts "speechRecognition", "imageSearch", and "textAnim" for more parameters to tweak.




</code></pre>
