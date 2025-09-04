# Kubernetes-a-traves-de-Ansible


## Pasos previos:

sudo useradd -m oloco
echo "oloco:oloco" | sudo chpasswd
sudo usermod -aG sudo oloco
echo "oloco ALL=(ALL) NOPASSWD: ALL" | sudo tee /etc/sudoers.d/oloco
