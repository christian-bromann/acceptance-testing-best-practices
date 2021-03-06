cucumberjs-cucumberjs-webdriverio
=================================
```
Test runner:       cucumber-js
Testing framework: cucumber-js
Front-end driver:  WebdriverIO
```

To run the tests:

- Make sure *Manage My Money* application is running

```bash
    # --- In command shell 1 ---
    $ cd Projects/manage-my-money-server
    $ npm start

    # --- In command shell 2 ---
    $ cd Projects/manage-my-money-client
    $ gulp serve-dev
```

- Run the Selenium Standalone Server:

```bash
    # --- In command shell 3 ---
    $ java -jar /usr/local/bin/selenium-server-standalone-2.47.1.jar
```

- Run the tests:

```bash
    # --- In command shell 4 ---
    $ cd <this-directory>
    $ npm install
    $ npm test
```

By default, the tests run in Chrome. To switch to another browser, change the `browserName` in `test/step_definitions/support/hooks.js`.
