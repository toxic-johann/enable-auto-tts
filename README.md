# enable-auto-tts
A script to let the web speech API can run programmatically under multiple platforms

On some platforms, the device has restrict on the Web Speech API.

For example, in iOS, the speech API doesn't work until it has triggered by the user interactive for once. That blocks us to use Web Speech API programmatically.

You can see the detail in this question. https://stackoverflow.com/questions/32193704/js-speech-synthesis-issue-on-ios/62587365#62587365

In order to fix this, I create this package. You can enable the auto TTS easily.

### install
```
npm install enable-auto-tts
```

### usage

You can enable by yourself

```
import { enableAutoTTS } from 'enable-auto-tts';

enableAutoTTS();
```
