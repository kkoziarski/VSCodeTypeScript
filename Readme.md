# Basic TypeScript config for VSCode

## Preconditions

```
├── bower@1.7.9
├── gulp@3.9.1
├── npm@3.10.5
├── typescript@1.8.10
└── typings@1.3.2
```

`cmd> tsc` should be declared globally and taken from `npm`  instead of  `C:\Program Files (x86)\Microsoft SDKs\TypeScript\1.8\` declared in **PATH**

## VSCode commands

Tasks for VSCode are declared in `.vscode/tasks.json`

`Ctrl+Shift+B` for building - compile .ts files

`Ctrl+P >> task 'tsc Build Type Script'`- alternative to build task

`Ctrl+Shift+P >> 'Tasks: Run Tasks' >> 'tsc Build Type Script'` - same as above

`Ctrl+P >> task 'ls'`- any other task name declared in `.vscode/tasks.json`

Output files are in `wwwroot/app/`

Test push to multiple remotes