# Coffe Grub Theme

What is it?
A cozy, vintage style GRUB theme with a warm coffe-like theme and a cafe like enviroment.

## Features
=>1920x1080 optimised

=> Gold brown colour palette

=> Minimal, immersive aesthetic

## Recommended File structure
grub-coffee-theme/

├── theme.txt

├── coffee_background.png

├── menu_card.png

├── menu_highlight.png

├── progress_fill.png

├── progress_bar.png

├── fonts/

│ ├── Lora-Regular.pf2

│ └── Lora-Bold.pf2

└── icons/

└── coffee_icon.png

## Installation
### Step 1:-
copy this theme into GRUB's theme directory
```Bash
sudo mkdir -p /boot/grub/themes/
sudo cp -r grub-coffee-theme /boot/grub/themes/
```

### Step 2:-
Edit /etc/default/grub and add (or update) this line:
```Bash
GRUB_THEME="/boot/grub/themes/grub-coffee-theme/theme.txt"
```

### Step 3:-
Regenarate GRUB
```Bash
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

### Reboot and enjoyyyy!!!!
