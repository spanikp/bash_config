# bash_config

This repository consist of files which can be sourced in bash shell session to replicate my "home" environment

## Setup bash using `bash_config`
1. Clone the repository
    ```bash
    $ git clone https://github.com/spanikp/bash_config.git ~/.bash_config
    ```
  
    Alternatively download zipped repository with `curl` and extract with `unzip`
    ```bash
    $ curl -L https://github.com/spanikp/bash_config/archive/refs/heads/main.zip --output -j temp.zip && unzip temp.zip -d ~/.bash_config && rm temp.zip
    ```
  

2. Source the bash shell session configuration files
    ```bash
    $ source ~/.bash_config/bash_config
    ```
