# 如何改变vps 的swapfile

```bash
sudo swapoff /swapfile
sudo rm /swapfile
sudo chmod 600 /swapfile
sudo mkswap /swapfile
sudo swapon /swapfile
```
