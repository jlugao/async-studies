Week 1
--------------

## Notes

- [Async Functions](https://trio.readthedocs.io/en/stable/tutorial.html#async-functions)
  - run every example and read everything here
  - don't forget to `await` for `async` functions because they return a coroutine object, not what you expected
  - `await` receives the coroutine object and runs it
  - watch out for `RuntimeWarning: Enable tracemalloc to get the object allocation traceback` this mean you forgot to await
  - `with` is a context manager
    - entering it calls `__enter__()`
    - exiting it calls `__exit__()`
  - `async with` is an async context manager
    - entering it calls `__aenter__()`
    - exiting it calls `__aexit__()`
  - The program [Hello Async](./hello_async.py) runs the first usefull program in trio's tutorial



## Homework

- Read [Task switching illustrated](https://trio.readthedocs.io/en/stable/tutorial.html#task-switching-illustrated)
- Read [A kinder, gentler GIL](https://trio.readthedocs.io/en/stable/tutorial.html#a-kinder-gentler-gil)