# 📦 Fastfetch Dotfile

Un dotfile personnalisé pour Fastfetch, permettant d'afficher un système d'information stylisé et optimisé.

## 🚀 Introduction

[Fastfetch](https://github.com/fastfetch-cli/fastfetch) est un outil rapide et hautement configurable pour afficher des informations sur votre système. Ce répertoire contient un fichier de configuration personnalisé (".config/fastfetch/config.jsonc").

## 🎨 Aperçu

![Aperçu de Fastfetch](https://github.com/PoudaLePanda/fastfetch-config/blob/main/capture.png)


## 📂 Installation

Tous les dotfiles dans '~/DOTFILES'

### 1. Cloner le répo
```sh
git clone https://github.com/PoudaLePanda/fastfetch-config.git ~/DOTFILES
```

### 2. Créer un lien symbolique vers le fichier de configuration
```sh
mkdir -p ~/.config/fastfetch
ln -s ~/DOTFILES/fastfetch-config/config.jsonc ~/.config/fastfetch/config.jsonc
```

### 3. Tester Fastfetch
```sh
fastfetch
```

## ⚙️ Personnalisation

`config.jsonc` personnalisé avec les couleurs de [catppuccin](https://catppuccin.com/).

## 💡 Exécution automatique
- Ajoutez `fastfetch` à votre `.bashrc` ou `.zshrc` pour l'exécuter automatiquement à chaque ouverture de terminal.
  ```sh
  echo "fastfetch" >> ~/.bashrc  # ou ~/.zshrc selon votre shell
  ```
- Explorez d'autres options avec : `fastfetch --help`

## 📜 Licence
MIT License - Faites-en ce que vous voulez ! 🎉

---

🌟 Si ce projet vous est utile, laissez une étoile sur GitHub !
