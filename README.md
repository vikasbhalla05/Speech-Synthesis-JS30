# Building the Intuition

1. Using a new instance of SpeechSynthesisUtterance API.
2. An Array of voices provide by the browser.
3. giving `msg.text` the value of of text area.
4. Add eventListener "voiceschanged" to speechSynthesis.
5. And run a function to `this.getVoices()` & create and inner html for the dropdown of voices with map and join.
6. Set voice with eventListener "change" on the dropdown and run setVoice function.
7. Set msg.voice find the voice from this.value in the voices array.
8. Create a toggle function to cancel and speak for the speechSynthesis with startOver.
9. Set for the message for this.name and this.value.
10. Add eventListenter for click on the speak & stop buttons and run function toggle
11. Filter the voices array with 'en' tag.