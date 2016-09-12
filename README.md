# What it does
  An ansible playbook that creates logical volumes backed by a xfs filesystem.
  
# Installation

    cp  inventory.example inventory
    cp group_vars/local.yaml.example group_vars/local.yaml

Edit both files according to your needs.

    ansible-playbook main.yml -i inventory
