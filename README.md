# Ansible Pull Playbook for Endeavour OS

This repository contains an Ansible pull playbook that can be used to set up Endeavour OS.

## Prerequisites

Before running the playbook, make sure you have the following prerequisites installed:

- Ansible
- Git

```bash
sudo pacman -S ansible git
```

## Usage

To use this playbook, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the cloned repository directory.
3. Run the Ansible pull command to execute the playbook:

    ```bash
    sudo ansible-pull -U https://github.com/grumpytinkerer/ansible_pull_endeavour_os.git
    ```

4. Wait while Ansible sets up Endeavour OS for you.

## Contributing

This repository is public, but for personal use. Please do not submit pull requests.

## Resources used in this repo
https://github.com/kewlfft/ansible-aur