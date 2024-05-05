# Compiling for Windows

### Getting Started

Recommended / Required Development Utilities

[NodeJS](https://nodejs.org/en)

[Bun](https://bun.sh)

### Git

Installing git on Windows can be done [here](https://git-scm.com/download/win)

Cloning the repository

Open a command prompt window in the directory where you want Git to clone, and enter the following command.

`git clone https://github.com/zolvy/AppleMusicElectron -b windows_dev`

## **Installing Dependencies**

Feel free to use any node package manager [pnpm](https://pnpm.io/), [Yarn](https://yarnpkg.com/), [npm](https://nodejs.org), [Bun](https://bun.sh), etc, run this command depending on your package manager.

`./utils/install.bat -bun`

## **Compiling AME**

Same command just a different file

`./utils/compile.bat`

## Installing AME

Congratulations! You can find the file in the /dist folder
