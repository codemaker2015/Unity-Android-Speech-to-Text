# Speech And Text in Unity Android
Speed to text and text to speed in Unity Android

## Demo

<img src="Demo/demo.gif" width="308" height="548" />

## Native Speech and Text
* SpeechToText Android: https://developer.android.com/reference/android/speech/package-summary.html
* TextToSpeed Android: https://developer.android.com/reference/android/speech/tts/TextToSpeech.html
* SpeechToText iOS: https://developer.apple.com/reference/speech
* TextToSpeech iOS: https://developer.apple.com/reference/avfoundation

## Android
* Hide default android popup, there's a bool to enable and disable if you don't want the popup to show up.
```
class SpeechToText
{
      public const bool isShowPopupAndroid = false;
      ...
```
* Merge file AndroidManifest (If you want skip the default popup)