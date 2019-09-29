# Test Automation in Page Object Model using Python 



# Goals

  - Learn the basics of web UI test automation with Python.
- Set up a good Python test automation project that can be extended with new     tests.
- Write and run a few example tests locally

# Tools used 
- Pytest
- Selenium
# Why Python
Python is one of the most popular programming languages currently available. It powers web backends, data science notebooks, sysadmin scripts, and more. Its syntax is clean, readable, and elegant – perfect for both beginners and experts. And everything you could imagine is just an import away. Naturally, Python is also a great language for test automation. Its conciseness lets testers focus more on the test and less on the code. Testers who haven’t done much programming tend to learn Python faster than other languages like Java or C#. Python is perfect for kickstarting tests!

# Why Pytest
At the heart of any functional test automation project is the “core” test framework. The framework handles test case structure, test execution, and pass/fail result reporting. It is the foundation upon which extra packages and code (like Selenium WebDriver) can be added.

pytest is one of Python’s best test frameworks. It is simple, scalable, and Pythonic. Test cases are written as functions, not classes. Test assertion failures are reported with actual values. Plugins can add code coverage, pretty reports, and parallel execution. pytest can integrate with other frameworks like Django and Flask, too. According to the Python Developers Survey 2018, pytest is also the most popular Python test framework.

### Tech

This project uses a number of open source projects to work properly:

* [Selenium Python](https://selenium-python.readthedocs.io/)- Selenium Python bindings provides a simple API to write functional/acceptance tests using Selenium WebDriver
* [Pytest](https://docs.pytest.org/en/latest/index.html) - The pytest framework makes it easy to write small tests, yet scales to support complex functional testing for applications and libraries


### Project Directory Layout

```sh
$ tree
.
├── Pipfile
├── Pipfile.lock
├── pages
│   ├── __init__.py
│   ├── result.py
│   └── search.py
└── tests
    ├──  test_web.py
    └──  conftest.py
    └──  config.json
```

How to run

```sh
$ pipenv run python -m pytest
===========================test session starts ===========================
platform win32 -- Python 3.7.4, pytest-5.1.3, py-1.8.0, pluggy-0.13.0
rootdir: C:\Users\shriv\Projects\PythonProjects\TeslaTestProject
collected 1 item                                                                                                                                                                

tests\test_web.py
DevTools listening on ws://127.0.0.1:63156/devtools/browser/74fe3c09-59a1-411b-b543-5a7931e1d33d
.                                                                                                                                                       [100%]

======================= 1 passed in 9.05s ================================

```
