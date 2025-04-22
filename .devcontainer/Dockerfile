FROM mcr.microsoft.com/devcontainers/universal:2-linux

# Install xz-utils (you may need it)
RUN apt-get update && apt-get install -y xz-utils

# Install Vue CLI with NVM
RUN bash -c "source /usr/local/share/nvm/nvm.sh && nvm use node && npm install -g @vue/cli"

# Install Flask using pip
RUN pip3 install flask