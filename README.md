# Ansible

Struktur 

etc/
├── ansible/
│   ├── inventory.ini
│   └── install_nginx.yml
└── README.md

Langkah pertama pastikan anda bisa ssh tanpa password ke dalam managed node yang dituju.
1. ssh-keygen -t rsa -b 4096
2. ssh-copy-id -p 22 xxx@xxxxx

   
periksa file inventory.ini pastikan ip, user, dan password.
