# v3

Third iteration of my personal website built with Jekyll.

> 📢 **PSA for those who want to fork or copy this repo and use it for their own site:**
>
> Please be a decent person and give me proper credit by linking back to my website! Refer to this handy [quora post](https://www.quora.com/Is-it-bad-to-copy-other-peoples-code) if you're not sure.

## Dependencies

- [Gulp](https://gulpjs.com/)
- [rbenv](https://github.com/rbenv/rbenv) (recommended for local Ruby)

## Ruby Setup (rbenv)

This project uses Jekyll and works best with a user-managed Ruby.

1.  Install rbenv and ruby-build (Homebrew):
    - `brew install rbenv ruby-build`
2.  Initialize rbenv for zsh:
    - `echo 'eval "$(rbenv init - zsh)"' >> ~/.zshrc`
    - `source ~/.zshrc`
3.  Install and select a Ruby version:
    - `rbenv install 3.3.4`
    - `rbenv global 3.3.4`
4.  Verify Ruby is coming from rbenv:
    - `ruby -v`
    - `which ruby`
5.  Install gems:
    - `gem install bundler jekyll jekyll-minifier jekyll-sitemap sass`

## Getting Started

1.  `npm install`
2.  `npm start`
