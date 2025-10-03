#Server Info
- OS: Linux
- User: opc
- Node.js version: v22.20.0
- npm version: 10.9.3
#Steps
1. SSH into Server in Terminal using public IP address and private ssh key
   1. ssh -i ssh-key-2025-10-01.key opc@143.47.117.27
2. Install Node.js using NVM with these commands
   1. curl -fsSL https://raw.githubusercontent.com/nvm-sh/nvm/master/install.sh | bash
   2. nvm install --lts
3. Create folder for code files
   1. mkdir myinstance
   2. cd my instance
4. Add code files with nano command
   1. nano index.js
   2. nano index.html
5. Install Node Express
   1. npm init -y
   2. npm install express
6. Test index.js file to see if it works
   1. node index.js
7. Type http://143.47.117.27:3000 into web browser to see if you can connect to the internet

