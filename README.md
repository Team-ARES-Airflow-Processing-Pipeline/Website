# Quinton's Starter Instructions

Hi there! So, in order to get this theme working properly, there are a few things that need to be done first:

1. Make sure you have ["Hugo Extended"](https://github.com/gohugoio/hugo/releases) installed, not just normal hugo
2. Have Go installed to your system

I imagine the website should load normally at this point when you run `hugo server`

But if it doesn't these steps should get you running:

```bash
# Run these commands from within the website directory
hugo mod get -u github.com/CaiJimmy/hugo-theme-stack/v3
hugo mod tidy
```
