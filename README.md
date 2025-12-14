# SSHRD_Script-fix-gaster-error

## This is a fork of: https://github.com/verygenericname/SSHRD_Script/blob/main/sshrd.sh

A fork of the sshrd.sh file to resolve the error: cannot find zipfile directory in one of gaster-Darwin.zip

## Usage

```bash
rm ./sshrd.sh && curl https://raw.githubusercontent.com/A11pwnX/SSHRD_Script-fix-gaster-error/refs/heads/main/sshrd.sh -o ./sshrd.sh && chmod +x ./sshrd.sh
```

## How does it work?

I simply change the Gaster download URL, which currently returns a 404 error, to https://static.palera.in/legacy/deps/

## diff
https://www.diffchecker.com/zque5Z7J/
