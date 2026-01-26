# 🎮 Minecraft Bedrock Server via Docker & Playit.gg

This repository contains the configuration to run a globally accessible Minecraft Bedrock server using Docker and Playit.gg tunnels. This project is a **Procedure Text** assignment for **MAN 2 Kota Bogor**.

---

## 🚀 Installation Procedure

### 1. Prerequisites
* Docker & Docker Compose installed on your system.
* A Playit.gg account and an active agent secret key.
* Git for version control.

### 2. Setup & Security
To keep our credentials safe, we use a `.env` file which is excluded from GitHub.

1.  **Clone the project:**
    ```bash
    git clone git@github.com:imambonjour/docker-bedrock.git
    cd docker-bedrock
    ```
2.  **Create the environment file:**
    Copy the provided example and fill in your secret key:
    ```bash
    cp .env.example .env
    ```
3.  **Add your secret key:**
    Open `.env` with a text editor and update the following line:
    ```text
    PLAYIT_SECRET_KEY=your_actual_secret_key_here
    ```

### 3. Deploying the Server
Run the containers in detached mode:
```bash
sudo docker compose up -d

## 👥 Group Members
* Name 1: Imam
* Name 2: Alyafi
