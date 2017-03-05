##  Web Audio - Configure

```js
// Connect the nodes
oscillator.connect(gainNode);
gainNode.connect(audioCtx.destination);

// Configure the nodes
gainNode.gain.value = 0.5;
oscillator.type = 'sine';
oscillator.frequency.value = 440; // Hz
```
