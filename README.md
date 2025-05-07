# Benfiles

Install on remote machine

Requirements:
* https://www.chezmoi.io/
* https://starship.rs/guide/#%F0%9F%9A%80-installation

```bash
# set my shell to zsh
sudo usermod -s /bin/zsh ben

# starship
sudo snap install starship

sh -c "$(curl -fsLS git.io/chezmoi)" -- init --apply benfoxall
```
