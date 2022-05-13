# react_and_jest
I found current version React has wrong configuration for Jest by default. I would like to how to fix this issue.

## Preparation

I installed node v14.19.2 using nvm.

```
nvm install v14.19.2
nvm use v14.19.2`
```

Then I created a react app using npx command.

```
npx create-react-app react-jest
cd react-jest
npm start
```


## Installing Jest

I installed Jest as lots of documentations suggest.

```
npm install --save-dev jest
```


then configured package.json.

```
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "jest",
    "eject": "react-scripts eject"
  },  
```

## Running Jest

```
npm test

No tests found related to files changed since last commit.
Press `a` to run all tests, or run Jest with `--watchAll`.

Watch Usage
 › Press a to run all tests.
 › Press f to run only failed tests.
 › Press q to quit watch mode.
 › Press p to filter by a filename regex pattern.
 › Press t to filter by a test name regex pattern.
 › Press Enter to trigger a test run.
 ```

 Press a.

 ```
  PASS  src/App.test.js
  ✓ renders learn react link (89 ms)

Test Suites: 1 passed, 1 total
Tests:       1 passed, 1 total
Snapshots:   0 total
Time:        4.208 s, estimated 5 s
Ran all test suites.

Watch Usage: Press w to show more.
```

OK. Everything looks fine.


