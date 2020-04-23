# ts-jest-25.5.0-alpha.0-custom-typings
https://github.com/kulshekhar/ts-jest/issues/1115#issuecomment-618702214
## Steps
1. Run `yarn`
2. Run `yarn test`
```
 PASS  __tests__/index.test.ts
  √ foo (2ms)

Test Suites: 1 passed, 1 total
Tests:       1 passed, 1 total
Snapshots:   0 total
Time:        0.946s
Ran all test suites.
```
3. Switch to the branch `update-to-ts-jest-25.5.0-alpha.0`
4. Run `yarn`
5. Run `yarn test`
```
 FAIL  __tests__/index.test.ts
  ● Test suite failed to run

    __tests__/index.test.ts:4:12 - error TS2558: Expected 0 type arguments, but got 1.

    4     $.ajax<number>("/foo")
                 ~~~~~~

Test Suites: 1 failed, 1 total
Tests:       0 total
Snapshots:   0 total
Time:        2.054s
Ran all test suites.
```
