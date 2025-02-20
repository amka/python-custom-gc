# Demo of Python custom GC settings


### Run without changing GC settings:

    ```
    > python ./demo.py
    Use modified GC settings? [y]/n n
    Total memory used: 14.58 MB.
    Total memory used: 174.81 MB.
    Done without modifying the GC.
    Memory used: 160 MB
    Time: 350.4 ms
    ```

### Run with changing GC settings:

    ```
    > python ./demo.py
    Use modified GC settings? [y]/n y
    Total memory used: 14.22 MB.
    Total memory used: 174.66 MB.
    Done with modifying the GC.
    Memory used: 160 MB
    Time: 149.2 ms
    ```
