# neovim
Neovim basic configuration for YAML, JSON, BASH, Ansible, Terraform, Python, Golang


### Requirements
1. Install npm: https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-20-04
2. Install python and pip.
3. Install go: https://go.dev/doc/install
4. Install brew: https://brew.sh/


### NeoVIM Configuration
1. Install NeoVIM: [](sadasiiaisdsjççç[]asds[]sadsd:)https://github.com/neovim/neovim/releases/tag/stable
2. Clone repository: `git clone https://github.com/helmcode/neovim.git ~/.config/nvim`
3. Install plugins `:PlugInstall`
4. Install` LSP Config

```bash
pip install ruff-lsp
pip install anakin-language-server
pip install pyright
pip install python-lsp-server
go install github.com/nametake/golangci-lint-langserver@latest
go install github.com/golangci/golangci-lint/cmd/golangci-lint@latest
brew install hashicorp/tap/terraform-ls
curl -s https://raw.githubusercontent.com/terraform-linters/tflint/master/install_linux.sh | bash
sudo npm i -g typescript typescript-language-server
sudo npm i -g vscode-langservers-extracted
sudo npm i -g yaml-language-server
sudo npm i -g @ansible/ansible-language-server
sudo npm i -g vscode-langservers-extracted
sudo npm i -g bash-language-server
````
