# typescript-start
A tool to download typescript type definition via read package.json

- step1: `npm install -g typescript-start`
- step2: `cd youproject`
- step3: `typescript-start`
this tool will read you project dependencies from package.json and put the Typescript type definition('*.d.ts') to youproject/typings.
and add all file reference to all.d.td.

# 中文说明：
这个工具通过读取package.json中的依赖来自动下载Typescript类型定义文件(*.d.ts)到typins文件夹，并在typing/all.d.ts中添加所文件的引用。
