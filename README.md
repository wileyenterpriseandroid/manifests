# Repo manifests for the example code for Wiley's Enterprise Android

## Getting the code

The best way to download the examples code,
is by using the Repo tool.  Get it like this:
```
curl https://dl-ssl.google.com/dl/googlesource/git-repo/repo > ~/bin/repo
```

Once repo is installed, download this source with the following commands:

```
repo init -u https://github.com/wileyenterpriseandroid/manifests.git
repo sync
```

You can download the source without using repo, with the following two commands:

```
git clone https://github.com/wileyenterpriseandroid/migrate-sdk.git
git clone https://github.com/wileyenterpriseandroid/Examples.git ea-examples
```

