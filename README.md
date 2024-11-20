# Configuration_CICD

### Tasks

0. Source the virtual environment `source /home/coder/venv/bin/activate`

1. Run the following steps of the `Makefile`:

`make lint`
`make format`
`make refactor`
`make test`

* Reflection Question:  Why does refactor combine `lint` and `format`?

2. Run the following command-line tool and then write a test for it using click test runner:

* Write a test for the `add_cli` functionality of the `main.py` function in the `test_main.py` test file.
* Use the test for for `./main.py --help` as a guide.  
* Reflection Question:  How could you use this style of testing to build MLOps tools quickly?
