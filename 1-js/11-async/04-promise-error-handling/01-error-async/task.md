# setTimeout 里的错误

<<<<<<< HEAD:1-js/11-async/04-promise-error-handling/01-error-async/task.md
你怎么看？`.catch` 会触发么？解释你的答案。
=======
What do you think? Will the `.catch` trigger? Explain your answer.
>>>>>>> 30e3fa723721909ee25115562e676db2452cf8d1:1-js/11-async/04-promise-error-handling/01-error-async/task.md

```js
new Promise(function(resolve, reject) {
  setTimeout(() => {
    throw new Error("Whoops!");
  }, 1000);
}).catch(alert);
```
