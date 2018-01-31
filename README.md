
# Reference

https://app-updates.agilebits.com/product_history/CLI


# Note

This is not the official NPM module. It is only a wrapper for binary/executable files downloaded from the reference above

AMD64 is here



# Usage:

```sh
export PLATFORM=$(node -e 'console.log(require(\"os\").platform())');
export PASSPATH=./node_modules/$PLATFORM;
chmod u+x $PASSPATH/op;
$PASSPATH/op # Check args from https://support.1password.com/command-line/.....
```
