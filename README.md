#Deploiement d' une app Streamlit iris sur une instance AWS EC2
## 1. Se connecter a son compte AWS via ala console et lancer une instance EC2
## Instructions pour installer et exécuter l'application Streamlit

### **NB : Utiliser le port :8501**

### 1. Mise à jour et préparation du système
Exécutez les commandes suivantes pour mettre à jour votre système et installer les dépendances nécessaires :
```
sudo apt update
```
```
sudo apt-get update
```
```
sudo apt upgrade -y
```
```
sudo apt install git curl unzip tar make sudo vim wget -y
```
### 2. Clonage du repertoire git
```
git clone "repertoire git"
```
### 3.Installer Python et les dépendances
```
sudo apt install python3-pip
```
```
pip3 install -r requirements.txt
```
### 4.Lancer l appli
```
###Lancement temporaire
python3 -m streamlit run app.py
```
```
### Lancement permanent
nohup python3 -m streamlit run app.py
```
```
