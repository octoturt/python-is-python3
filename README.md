# python-is-python3

A script that creates a symlink to Homebrew's `python3` binary. Serves the same purpose as Ubuntu's [`python-is-python3`](https://packages.ubuntu.com/focal/python-is-python3) package.

## Installation
1. Install [Homebrew](https://docs.brew.sh/Installation) if you have not already.
2. Tap my homebrew repository:

        % brew tap octoturt/repository
              
3. Install `python-is-python3`: 

        % brew install python-is-python3
        
4. Test `python`:

```
% which python
/usr/local/bin/python
% python --version
Python 3.11.4
```