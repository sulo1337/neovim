## Neovim

My Neovim config.

## Prerequisites
Neovim version >0.9.0

## Usage
```sh
git clone https://github.com/sulo1337/neovim ~/.config/nvim && nvim
```

## Notes
- This is a fork from [NvChad](https://github.com/NvChad/NvChad) neovim config
- Might need to install additional golang packages for golang LSP to work

### Golang Setup Dependencies
Some dependencies needs to be installed for golang to correctly work.

Install gofumpt - a stricter formatting for go:
```sh
go install mvdan.cc/gofumpt@latest
```

Install goimports-reviser:
```sh
go install -v github.com/incu6us/goimports-reviser/v3@latest
```

Install golines - a long line shortner for go:
```sh
go install github.com/segmentio/golines@latest
```
