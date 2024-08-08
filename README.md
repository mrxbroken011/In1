<a href="https://heroku.com/deploy?template=https://github.com/mrxbroken011/In1" target="_blank">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy to Heroku" />
</a>

---

### 🌟 Features

- 🎵 **Multiple Sources:** Play music from various platforms.
- 📃 **Queue System:** Line up your favorite songs.
- 🔀 **Advanced Controls:** Shuffle, repeat, and more.
- 🎛 **Customizable Settings:** From equalizer to normalization.
- 📢 **Crystal Clear Audio:** High-quality playback.
- 🎚 **Volume Mastery:** Adjust to your preferred loudness.

---

### 🔧 Quick Setup

1. **Upgrade & Update:**
   ```bash
   sudo apt-get update && sudo apt-get upgrade -y
   ```

2. **Install Required Packages:**
   ```bash
   sudo apt-get install python3-pip ffmpeg -y
   ```
3. **Setting up PIP**
   ```bash
   sudo pip3 install -U pip
   ```
4. **Installing Node**
   ```bash
   curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash && source ~/.bashrc && nvm install v18
   ```
5. **Clone the Repository**
   ```bash
   git clone https://github.com/TeamAviax/AviaxMusic && cd AviaxMusic
   ```
6. **Install Requirements**
   ```bash
   pip3 install -U -r requirements.txt
   ```
7. **Create .env  with sample.env**
   ```bash
   cp sample.env .env
   ```
   - Edit .env with your vars
8. **Editing Vars:**
   ```bash
   vi .env
   ```
   - Edit .env with your values.
   - Press `I` button on keyboard to start editing.
   - Press `Ctrl + C`  once you are done with editing vars and type `:wq` to save .env or `:qa` to exit editing.
9. **Installing tmux**
    ```bash
    sudo apt install tmux -y && tmux
    ```
10. **Run the Bot**
    ```bash
    bash start
    ```

---

### 🛠 Commands & Usage

The Aviax Music Bot offers a range of commands to enhance your music listening experience on Telegram:

| Command                 | Description                                 |
|-------------------------|---------------------------------------------|
| `/play <song name>`     | Play the requested song.                    |
| `/pause`                | Pause the currently playing song.           |
| `/resume`               | Resume the paused song.                     |
| `/skip`                 | Move to the next song in the queue.         |
| `/stop`                 | Stop the bot and clear the queue.           |
| `/queue`                | Display the list of songs in the queue.     |

For a full list of commands, use `/help` 
---

### 🔄 Updates & Support

Stay updated with the latest features and improvements to Aviax Music Bot:



---

### 🤝 Contributing

We welcome contributions to the Aviax Music Bot project. If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch with a meaningful name.
3. Make your changes and commit them with a descriptive commit message.
4. Open a pull request against our `main` branch.
5. Our team will review your changes and provide feedback.

For more details, reach out us on telegram.

---

### 📜 License

This project is licensed under the MIT License. For more details, see the [LICENSE](LICENSE) file.

---

### 🙏 Acknowledgements

Special thanks to all the contributors, supporters, and users of the Aviax Music Bot. Your feedback and support keep us going!
- [Yukki Music](https://github.com/TeamYukki/YukkiMusicBot) and [AnonXMusic](https://github.com/AnonymousX1025/AnonXMusic) For their Source Codes.

