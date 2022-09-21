# Runner
Project created in order to develop low-level programming ideas
**TLDR:** CLI OS single threaded features built on Rust.

## Document structure
- Aimed to be a modular set of functions that could be used together with ease of use
- 

## First Interests:
- Interface with user
    - Maintain Config. stable connection 
    - Get input() for:
        - ExpressionEvaluator
            - Start with simple statements in Linux shell
            - Work towards implementing bigger things
                - How to handle multiple workloads at a time
                - How to schedule them on the background
                    - Linux Daemon open source implementation
                - Interact with scheduler only (CRUD Workloads API)



## API
- core 
    - input/output
        - receive
        - print
- init()
    - value = receive()
    - print(value)
    - return 0