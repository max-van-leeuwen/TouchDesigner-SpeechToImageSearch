# TouchDesigner-SpeechToImageSearch
TouchDesigner experiment: Real-time Speech-to-Text using Microsoft Azure, to search for images online and display them instantly.

A stable internet connection is required, as this project does online speech recognition via Azure and constantly fetches image search results.


<pre><code>
maxvanleeuwen.com
twitter	@maksvanleeuwen
ig 	@max.van.leeuwen

Dependencies:
	Azure Cognitive Services 	https://pypi.org/project/azure-cognitiveservices-speech/
	Selenium 			https://pypi.org/project/selenium/
	Internet Archive 		https://pypi.org/project/internetarchive/

Setup:
	Enter your Azure Key and Region in the speechRecognition script.
	Make sure the 'chromedriver' file is next to this toe. Chrome is used in the background to get the images to display.

How to use:
	Toggle 'showUI' to show or hide the UI elements in Perform Mode.
	When 'speechToggleButton' is on, speech recognized in the speech recognition module will be used. The module is always running in the background.
	To add text by keyboard, use the 'keybInput' field and the 'addKeybInputButton' button.
	Use 'TrailSlider' and 'textSizeSlider' to customize the rainbow text.
	Open the scripts "speechRecognition", "imageSearch", and "textAnim" for more parameters to tweak.
</code></pre>
