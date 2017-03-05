##  Web Audio - Context

```js
// Create a context for audio operations
const audioCtx = new (window.AudioContext || window.webkitAudioContext)();

// Create a basic tone oscillator with gain (volume) control
const oscillator = audioCtx.createOscillator();
const gainNode = audioCtx.createGain();
```
