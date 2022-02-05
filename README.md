# `gpg-gen`

This script was heavily inspired and derived from the instructions in this guide: [drduh/YubiKey-Guide](https://github.com/drduh/YubiKey-Guide)

## Usage:

If you want to use [drduh/config/gpg.conf](https://github.com/drduh/config/blob/master/gpg.conf):

```
curl -O https://raw.githubusercontent.com/drduh/config/master/gpg.conf
```

or

```
wget https://raw.githubusercontent.com/drduh/config/master/gpg.conf
```

Otherwise, place your own configuration in a file called `gpg.conf` in the same directory as `gpg-gen`. (TODO: Make this configurable)

```
./gpg-gen --name='Matt Helm' --email='matt.helm@mehnet.io' --output-dir="${HOME}/Downloads"
```
