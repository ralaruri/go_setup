## Setup 

### Installing Go using asdf
- This is how I manage my local Python installations 
- I am not sure if there is ever an instance I would need a later or beta version of Go.


1. Installing asdf using homebrew
- `brew install asdf`
- `echo -e "\n. $(brew --prefix asdf)/libexec/asdf.sh" >> ~/.zsh_profile`


2. Installing go 
- `asdf plugin add go`
- `asdf install go latest`

3. Setting a Version 
- `asdf global go latest`
if you need to a set a local env.
- `asdf local go latest`




