# Raspberry-Pi
This is a list of script made by me to easily install stuff on your raspberry pi running on the PiOS


Pterodactyl panel script :
curl -fsSL https://raw.githubusercontent.com/noxshade0/Raspberry-Pi/refs/heads/main/Pterodactyl-Panel | sudo bash -

You can add an user by typing :
php artisan p:user:make \
  --email="newuser@example.com" \
  --username="newuser" \
  --name-first="New" \
  --name-last="User" \
  --password="StrongPassword123" \
  --admin=1

 or just by typing 
 php artisan p:user:make
