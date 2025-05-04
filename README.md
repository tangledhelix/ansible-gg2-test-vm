- Start from a general Ubuntu VM
- Install `ansible`
    - `sudo apt-get update`
    - `sudo apt-get install -y ansible`
- Clone this repository
- Run the `main.yml` playbook against local system as the default user, possibly `ubuntu`, or whatever user you plan to use ...
    - `ansible-playbook --ask-become-pass main.yml`

Sets up Guiguts 2 in ~/guiguts-py and Guiguts 1 in ~/guiguts.

Installs my dotfiles.
