# Newwww-Folder
sudo apt update

sudo apt install -y make build-essential libssl-dev zlib1g-dev


libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm

libncursesw5-dev xz-utils tk-dev libxml2-dev libxmlsec1-dev libffi-dev liblzma-dev

curl https://pyenv.run | bash

echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bashrc

echo 'command -v pyenv >/dev/null || export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bashrc

echo 'eval "$(pyenv init -)"' >> ~/.bashrc

source ~/.bashrc # Or ~/.zshrc

pyenv install 3.10.12 # Or the latest 3.10.x version available
