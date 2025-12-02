# addpath
add a path to the linux PATH

# Installation
sudo cp addpath /usr/local/bin/
sudo chmod +x /usr/local/bin/addpath

# Add current directory to PATH (current session only)
./addpath

# Add permanently to your shell config (.bashrc, .zshrc, etc.)
./addpath --permanent

# For immediate effect in current shell, use 'source'
source ./addpath

cd /home/user/my-scripts
./addpath                    # Adds /home/user/my-scripts to PATH

# Make it permanent
./addpath --permanent        # Writes to ~/.bashrc or ~/.zshrc
