# Quinton's setup instructions

Hi there! Here are some quick instructions for how to set up the website development environment,

Before we get started, we have to make sure that some things have been done first:

1. Make sure you have ["Hugo Extended"](https://github.com/gohugoio/hugo/releases) installed, not the regular Hugo version
2. Make sure you have the latest version of the Go language installed


Once those conditions have been met, clone the repo in a sensible place

Run the following command to install the template:

```bash
# Run this from within the website directory
git submodule update --init --recursive
```

At this point, the server should run when you execute `hugo server`
