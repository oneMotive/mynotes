- ssh-keygen -t ed25519 -C "your_email@example.com"
- eval "$(ssh-agent -s)"
- ssh-add ~/.ssh/id_ed25519
- Add public key to Github
- ssh -T git@github.com
- git remote set-url origin <new.git.ssh.url>
https://docs.github.com/en/get-started/git-basics/managing-remote-repositories
