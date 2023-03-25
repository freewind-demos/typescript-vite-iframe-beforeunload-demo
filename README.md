TypeScript Vite IFrame "beforeunload" Event Demo
====================

一个iframe，如果是常规的跳转（比如手动点击右键 Reload frame或者 window.location.href="???", 则：`beforeunload`与`unload`事件都会触发

如果是其它的方式，比如代码中`iframe.remove()`，则： `unload`事件会触发，但`beforeunload`不会触发


```
npm install
npm start
```

It will open page on browser automatically.
