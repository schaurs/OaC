# OaC Collection

Configuration as Code collection for Ansible Automation Platform.

## Description

This collection provides playbooks, roles, and modules for managing infrastructure configuration as code using Ansible Automation Platform.

## Requirements

- Ansible >= 2.9
- Ansible Automation Platform (optional, for webhook integration)

## Installation

### Install from Galaxy
```bash
ansible-galaxy collection install schaurs.oac
```

### Install from source
```bash
ansible-galaxy collection install git+https://github.com/schaurs/OaC.git
```

## Usage

### Running the hello playbook
```bash
ansible-playbook schaurs.oac.hello
```

### Webhook Integration
This collection includes webhook payload handling for integration with GitOps workflows.

## Contributing

Please read the [contributing guidelines](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the GPL-2.0-or-later License - see the [LICENSE](LICENSE) file for details.