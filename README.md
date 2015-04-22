# typescript-start
A tool to download typescript type definition via read package.json

- step1: `npm install -g typescript-start`
- step2: `cd youproject`
- step3: `typescript-start`
this tool will read you project dependencies from package.json and put the typescript type Definition('*.d.ts') to youproject/typings.
and add all file reference to all.d.td.

