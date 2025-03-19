# Use an ARM64-compatible Node.js image for Apple Silicon
FROM --platform=linux/arm64 mcr.microsoft.com/vscode/devcontainers/javascript-node:18

# Install Angular CLI globally
RUN npm install -g @angular/cli

# Install Expo CLI globally
RUN npm install -g expo-cli

# Install React Native CLI globally
RUN npm install -g react-native-cli

# Install Yarn
RUN npm install -g yarn

# Install additional tools
RUN npm install -g typescript eslint prettier

# Set working directory
WORKDIR /workspace
