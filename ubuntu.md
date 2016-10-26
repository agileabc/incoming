
# Set node version manually. http://askubuntu.com/questions/426750/how-can-i-update-my-nodejs-to-the-latest-version

### Install n, and make it pointing to latest "stable" version. 

```
sudo npm cache clean -f
sudo npm install -g n
sudo n stable
```

### Create symlink to make "/usr/bin/node" pointing to "/usr/local/n/versions/node/7.0.0/bin/node". 

```
sudo ln -sf /usr/local/n/versions/node/7.0.0/bin/node /usr/bin/node
```

### Verify it. 

```
node -v
```


