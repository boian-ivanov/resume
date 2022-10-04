## Resume repository
This repository holds my current resume, using the [JSON Resume standard](https://jsonresume.org/).
It is build with the [json resume cli](https://github.com/jsonresume/resume-cli) tool and the [jsonresume-theme-actual](https://github.com/davcd/jsonresume-theme-actual) theme.
Current compiled version, is found [here](resume.pdf).

## Instructions
To edit and/or compile it, you need to install the json resume cli tool:
```bash
yarn global add resume-cli
```

Then, you can edit the resume.json file, and compile it with:
```bash
yarn generate
```
