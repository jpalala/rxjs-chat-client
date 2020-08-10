# Things I learned from rxjs-chat-client

- [takeUntil](https://www.learnrxjs.io/learn-rxjs/operators/filtering/takeuntil)
  - Emit values until provided observable emits.

- [distinctUntilChanged](https://rxjs-dev.firebaseapp.com/api/operators/distinctUntilChanged)
  - Returns an Observable that emits all items emitted by the source Observable that are distinct by comparison from the previous item.

- [throttleTime](https://rxjs-dev.firebaseapp.com/api/operators/throttleTime)
  - Emits a value from the source Observable, then ignores subsequent source values for duration milliseconds, then repeats this process.
  - useful for rate limiting.

- [skipWhile](https://www.learnrxjs.io/learn-rxjs/operators/filtering/skipwhile) 
  - Skip emitted values from source until provided expression is false.

