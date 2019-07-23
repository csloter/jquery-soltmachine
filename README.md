# jquery-soltmachine
jquery 老虎机，可设置停止位置

## 使用
```
// machine init.
var machine = $("#machine").slotMachine({
    active  : 0,
    delay   : 800
});

machine.shuffle(5);
// set stopIndex 
var stopIndex = ...
machine.stopIndex(stopIndex);
// stop machine
machine.stop;

```
That's all.
### Just fork from https://josex2r.github.io/jQuery-SlotMachine/
