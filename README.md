# angular-cli-docker

## Usage

Run from console:

    $ docker run -i --rm -v "$PWD":/app hochzehn/angular-cli version
     
We recommend running a specific version for predictability of behaviour. The versions match [angular-cli releases](https://github.com/angular/angular-cli/releases); however, only [selected versions are available](/releases).

    $ docker run -i --rm -v "$PWD":/app hochzehn/angular-cli:6.2.2 version
    