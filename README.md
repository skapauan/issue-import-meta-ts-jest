# issue-import-meta-ts-jest

 Jest testing a Node ES module that uses import.meta encounters `error TS1343: The 'import.meta' meta-property is only allowed when the '--module' option is 'es2020', 'esnext', or 'system'`, even with the mentioned configuration set.

This shows the issue using ts-jest, but [a similar issue occurs using babel-jest](https://github.com/skapauan/issue-import-meta-babel-jest).


 ## Scripts

 `npm test` encounters the error.

 `npm start` (tsc and run the output) does not.
  