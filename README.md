# nginx

Role which is meant to install Nginx from scratch and configure it depending on the OS.

### Prerequisites

* roles: **ramdisk**
* Set your websites and users where their documents_roots will be in vars or group_vars.

## Deployment

Run ```ansible-playbook -i '<IP>,' playbooks/nginx.yml ``` (You will need to create your playbook first.)

## Built With

* [Ansible 2.8](https://docs.ansible.com/ansible/latest/roadmap/ROADMAP_2_8.html) - Ansible 2.8

## Authors

* **Valentin Dzhorov** - *Initial work* - [vdzhorov](https://github.com/vdzhorov)

## Company
* **Delta.BG**

## License

This project is licensed under the MIT License.
