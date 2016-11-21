# typescript-for-testcases
testing gamebook API for TGG games

Typescript is a language, which uses node.js to run its code. 
What I have to do to run test cases,
1. edit .ts, which contains testing contents.
2. edit package.json, which controls enviroment varaibles and the files to run.
3. type the npm command and run.

applied skills:
1. mocha, defining testcases
2. promise, receiving responses from API calls(e.g. http requests, DB calls)
3. async, await (get the response only when i get response and i really do get it)
4. assert (simalar to java, catching failed assertion by using try catch)
5. DB calls, http calls

useful links:
https://www.npmjs.com/package/mocha-typescript#scafolding
http://docs.sequelizejs.com/en/latest/docs/raw-queries/
https://www.kancloud.cn/kancloud/promises-book/44248
https://github.com/request/request-promise