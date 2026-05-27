# 🌌 Hyprland + Noctalia Dotfiles

Um ambiente Wayland minimalista, modular e de alta performance, construído do zero para o **Fedora Linux**. 

Este setup foi projetado para maximizar a produtividade no desenvolvimento de software, substituindo ferramentas tradicionais (como Waybar e Hyprpaper) pelo ecossistema unificado do **Noctalia**, garantindo menos consumo de recursos e zero conflitos visuais.

## 🛠️ Tecnologias e Ferramentas

* **Compositor / WM:** [Hyprland](https://hyprland.org/)
* **Shell / UI / Wallpaper:** [Noctalia](https://github.com/noctalia) (Interface IPC via `qs`)
* **Lock Screen:** `hyprlock` (Customizado com Blur, Relógio Dinâmico e DPMS)
* **Idle Manager:** `hypridle` (Gerenciamento de energia e suspensão)
* **Terminal:** Alacritty
* **Captura de Tela:** Gradia (Modo interativo com edição)
* **Gerenciador de Arquivos:** Thunar

## 📂 Estrutura de Diretórios

A configuração foi dividida em módulos para facilitar a manutenção:

```text
~/.config/hypr/
├── hyprland.conf           # Arquivo principal (Monitores, Env Vars da NVIDIA, Autostart)
├── hypridle.conf           # Regras de inatividade e suspensão da tela
├── hyprlock.conf           # Design premium da tela de bloqueio
└── configs/
    ├── animation.conf      # Curvas de Bézier e animações (Fluent/Pop-in)
    ├── noctalia-desing.conf# Gaps, bordas arredondadas, sombras e blur
    ├── window-bind.conf    # Todos os atalhos de teclado e mouse
    └── window-rules.conf   # Regras de flutuação e foco (ex: Noctalia, Rofi)
