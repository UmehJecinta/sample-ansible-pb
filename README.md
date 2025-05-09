Ansible Deployment for Django Poll App

This playbook installs dependencies, clones the Django project, and sets up Gunicorn and Nginx for production deployment.

Run:
ansible-playbook -i inventory ansible/deploy_django.yml
