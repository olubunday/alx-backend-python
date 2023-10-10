<h1>0x02. Python - Async Comprehension</h1>
<h2>Task 0</h2>
<i><strong>File - 0-async_generator.py</strong></i>
<p>Write a coroutine called `async_generator` that takes no arguments.

The coroutine will loop 10 times, each time asynchronously wait 1 second, then yield a random number between 0 and 10. Use the `random` module.</p>

<h2>Task 1</h2>
<i><strong>File - 1-async_comprehension.py</strong></i>
<p>Import `async_generator` from the previous task and then write a coroutine called `async_comprehension` that takes no arguments.

The coroutine will collect 10 random numbers using an async comprehensing over `async_generator` , then return the 10 random numbers.</p>

<h2>Task 2</h2>
<i><strong>File - 2-measure_runtime.py</strong></i>
<p>Import async_comprehension from the previous file and write a measure_runtime coroutine that will execute async_comprehension four times in parallel using asyncio.gather.

measure_runtime should measure the total runtime and return it.

Notice that the total runtime is roughly 10 seconds, explain it to yourself.</p>
