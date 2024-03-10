let speech = new SpeechSynthesisUtterance();

let voices = [];
let voiceSelect = document.querySelector("select");

let btn = document.querySelector("button");
btn.addEventListener("click" , ()=>{
    speech.text = document.querySelector("textarea").value;
    window.speechSynthesis.speak(speech);
});