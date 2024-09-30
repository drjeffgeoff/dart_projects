# dart_projects

1.Setting Up Dart on Ubuntu
Install Dart SDK:

Open the terminal (Ctrl + Alt + T).
Add the Dart stable repository:

Copy code
sudo apt update
sudo apt install apt-transport-https
sudo sh -c 'wget -qO- https://dl-ssl.google.com/linux/linux_signing_key.pub | apt-key add -'
sudo sh -c 'wget -qO- https://storage.googleapis.com/download.dartlang.org/linux/debian/dart_stable.list > /etc/apt/sources.list.d/dart_stable.list'

2. Install the Dart SDK:


Copy code
sudo apt update
sudo apt install dart

3. Confirm the installation:

Copy code
dart --version
