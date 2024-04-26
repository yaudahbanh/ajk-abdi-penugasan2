# Penugasan 2 Oprec AJK
| NRP | Nama Lengkap |
|----------|----------|
| 5025221043 | Tunas Abdi Pranata |

## Struktur Direktori

```
── ansible.cfg
├── env
│   └── vars.yml
├── inventory.ini
├── playbooks
│   ├── build.yml
│   ├── deploy.yml
│   ├── main.yml
│   ├── migrate.yml
│   └── prepare.yml
└── roles
    ├── backend-build
    │   ├── defaults
    │   │   └── main.yml
    │   ├── files
    │   ├── handlers
    │   │   └── main.yml
    │   ├── meta
    │   │   └── main.yml
    │   ├── README.md
    │   ├── tasks
    │   │   └── main.yml
    │   ├── templates
    │   │   ├── be-template.j2
    │   │   └── env-template
    │   ├── tests
    │   │   ├── inventory
    │   │   └── test.yml
    │   └── vars
    │       └── main.yml
    ├── backend-deploy
    │   ├── defaults
    │   │   └── main.yml
    │   ├── files
    │   ├── handlers
    │   │   └── main.yml
    │   ├── meta
    │   │   └── main.yml
    │   ├── README.md
    │   ├── tasks
    │   │   └── main.yml
    │   ├── templates
    │   │   └── be-template.j2
    │   ├── tests
    │   │   ├── inventory
    │   │   └── test.yml
    │   └── vars
    │       └── main.yml
    ├── backend-migrate
    │   ├── defaults
    │   │   └── main.yml
    │   ├── files
    │   ├── handlers
    │   │   └── main.yml
    │   ├── meta
    │   │   └── main.yml
    │   ├── README.md
    │   ├── tasks
    │   │   └── main.yml
    │   ├── templates
    │   │   └── env-template
    │   ├── tests
    │   │   ├── inventory
    │   │   └── test.yml
    │   └── vars
    │       └── main.yml
    ├── frontend-build
    │   ├── defaults
    │   │   └── main.yml
    │   ├── files
    │   ├── handlers
    │   │   └── main.yml
    │   ├── meta
    │   │   └── main.yml
    │   ├── README.md
    │   ├── tasks
    │   │   └── main.yml
    │   ├── templates
    │   ├── tests
    │   │   ├── inventory
    │   │   └── test.yml
    │   └── vars
    │       └── main.yml
    ├── frontend-deploy
    │   ├── defaults
    │   │   └── main.yml
    │   ├── files
    │   ├── handlers
    │   │   └── main.yml
    │   ├── meta
    │   │   └── main.yml
    │   ├── README.md
    │   ├── tasks
    │   │   └── main.yml
    │   ├── templates
    │   │   └── nginx-frontend.j2
    │   ├── tests
    │   │   ├── inventory
    │   │   └── test.yml
    │   └── vars
    │       └── main.yml
    ├── mysql-prepare
    │   ├── defaults
    │   │   └── main.yml
    │   ├── files
    │   ├── handlers
    │   │   └── main.yml
    │   ├── meta
    │   │   └── main.yml
    │   ├── README.md
    │   ├── tasks
    │   │   └── main.yml
    │   ├── templates
    │   ├── tests
    │   │   ├── inventory
    │   │   └── test.yml
    │   └── vars
    │       └── main.yml
    └── nginx-prepare
        ├── defaults
        │   └── main.yml
        ├── handlers
        │   └── main.yml
        ├── meta
        │   └── main.yml
        ├── README.md
        ├── tasks
        │   └── main.yml
        ├── templates
        │   └── nginx-config.j2
        ├── tests
        │   ├── inventory
        │   └── test.yml
        └── vars
            └── main.yml
```

- ansible.cfg: This file likely contains configuration settings for your Ansible project.
- env: This directory may contain environment-specific variables, likely stored in vars.yml.
- inventory.ini: This file probably contains the inventory of hosts that Ansible will manage.
- playbooks: This directory holds your Ansible playbooks, which are YAML files defining tasks to be executed.
- build.yml, deploy.yml, migrate.yml, prepare.yml: These are the playbooks for different stages of your deployment process.
- main.yml: This could be a main playbook that includes other playbooks or tasks.
- roles: This directory contains Ansible roles, which are reusable units of tasks, handlers, variables, etc.
Each role directory under roles corresponds to a specific task or component of your infrastructure.
Inside each role directory:
    - defaults/main.yml: Default variables for the role.
    - files: Any static files needed by the role.
    - handlers/main.yml: Handlers that are triggered by tasks in the role.
    - meta/main.yml: Metadata about the role, such as dependencies.
    - README.md: Documentation about the role.
    - tasks/main.yml: The main tasks executed by the role.
    - templates: Jinja2 templates used by the role.
    - tests: Tests for the role.
    - vars/main.yml: Additional variables specific to the role.
# Documentation
![image](https://github.com/yaudahbanh/ajk-abdi-penugasan2/assets/39010800/f8dd2f2d-6c00-4638-af1e-a1e6f3a391f8)
![image](https://github.com/yaudahbanh/ajk-abdi-penugasan2/assets/39010800/04435746-a917-48e1-b762-3a7fe9685234)
![image](https://github.com/yaudahbanh/ajk-abdi-penugasan2/assets/39010800/28682be7-6754-4665-b27c-0de94061f1c8)


