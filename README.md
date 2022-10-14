[![Build Image and Push to Quay](https://github.com/paulbarfuss/rosa-ansible-ee/actions/workflows/main.yml/badge.svg)](https://github.com/paulbarfuss/rosa-ansible-ee/actions/workflows/main.yml)

# rosa-ansible-ee

Ansible Automation Platform Execution Environment for ROSA and AWS

## Local development

Create the context directory

```bash
ansible-builder create
```

Build the image

```bash
ansible-builder build -t quay.io/pbarfuss/rosa-ansible-ee
```
