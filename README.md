<div align="center">

# guya-dl

`guya-dl` is a script to automate the downloading of manga from [guya.moe](https://guya.moe).

</div>

## Example Usage
```shell
# Download or update "Kaguya-sama: Love is War" in the directory `guya`
$ guya-dl

# Set output directory to download into or update
$ guya-dl -o output_dir

# List available series
$ guya-dl -l

# Download or update non-default list of manga series
$ guya-dl Kaguya-Wants-To-Be-Confessed-To We-Want-To-Talk-About-Kaguya
```

## Installation
1. Copy `guya-dl` to somewhere in PATH
2. Add execute permissions to `guya-dl`

## Dependencies
- [curl](https://curl.se)
- [jq](https://stedolan.github.io/jq/)
- [unzip](http://infozip.sourceforge.net/UnZip.html)

**Note:** the output directory format is unstable and may change before version 1.0
