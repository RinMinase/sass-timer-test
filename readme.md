# SASS/SCSS Timer Test

## Introduction
This is to test the compilation time of the current dart-sass implementation versus the node-sass (deprecated) implementation.

This uses the latest bootstrap package to test both implementations of SCSS/SASS compilers

## How to Run

**Prerequisites:**
- Latest LTS version of Node

1. Clone the repository

  ```
  git clone https://github.com/RinMinase/sass-timer-test.git
  ```

2. Install the required dependencies

  ```
  npm install
  ```

  This installs, sass (JS implementation of libsass), node-sass (deprecated libsass implementation)

3. Test both the implementation

  ```
  npm start
  ```

4. Test either implementations

  ```
  npm run sass
  ```

  ```
  npm run node-sass
  ```
