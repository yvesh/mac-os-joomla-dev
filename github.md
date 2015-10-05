# Setup GitHub

#### Generate a private key (for ssh access)

```ssh-keygen -t rsa -C "your@mail.com"```

**Add it to Github:**

```
# Copy the public key to your clipboard
pbcopy < ~/.ssh/id_rsa.pub
```

Paste the public key to the SSH-Key section at github.com

**Test connection**

ssh -T git@github.com

#### Setup global config

```
git config --global user.name "Your name" && \
git config --global user.email "your@email.com"

```




