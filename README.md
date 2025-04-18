# Pool Game

This is a simple physics simulation to help practice and get experience with handling rigidbody collisions. 

![](SFMLpoolgame.gif)

## How to run

 - clone repo
 - make sure you have a [rust](https://www.rust-lang.org/) compiler installed at version 1.82 or later
 - make sure you have cmake (make sure it's version 3 as version 4 seems to break it)
    - windows:
      ```
      winget install -e --id Kitware.CMake -v 3.25.3
      ```
    - mac:
       - install homebrew package manager
         ```
         /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
         ```
       - use homebrew to install cmake
         ```
         brew install cmake@3.25.3
         ```
    - linux:
       - use your package manager to install cmake (version 3.25.3)
 - linux has some extra dependencies that can be found [here](https://crates.io/crates/sfml/0.24.0)
 - be sure to cd into repo from a terminal application
 - run `cargo build` to build the exe in target/debug
 - you can either double click the exe in target/debug or use `cargo run` to run the program
