FROM ://microsoft.com
IMAGE_FEATURE=common-utils

# Install standard Linux system tools
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends \
    curl \
    wget \
    git \
    build-essential \
    sudo \
    htop \
    neofetch

# Give the default user passwordless sudo access
RUN echo "vscode ALL=(ALL) NOPASSWD:ALL" >> /etc/sudoers
