# README


## Installation

Clone project to server and use `installation.yml` ansible playbook to install API service. Installation script is initialized for user `ubuntu` and it is currently hard coded in many places (ex. directory `/home/ubuntu/...`).

```
ansible-playbook -i "server.ip.adress," installation.yml --check
ansible-playbook installation.yml --check
```

### Notes

These files are large and are ignored in `.gitignore`:

```
bert_best_finetuned.h5
neuro2.db
PubMed_daily/
```

