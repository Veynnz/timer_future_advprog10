# Module 10

### 1. Print Task Explanation

The last print statement was executed first because the other two are spawned inside the executor as an async task. They would be called only if the `executor.run()` is called, which is located at the end of the function, meaning that they would be called last, after the "hey hey" statement.