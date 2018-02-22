::

    - name: Ansible Meetup
      hosts: Sainsbury's Holborn Office
      vars:
        date: 2018-02-21
        link: https://www.meetup.com/Ansible-London/events/247309065/
        sponsors:
          - F5 Networks for Pizza
          - Sainsbury's for beverages
      tasks:
        - name: Ansible Roles
          presentation:
            by: Matthew & James, F5 Networks
            document: 01-Ansible-Roles-F5.pptx
            abstract: |
              An introduction to Ansible roles and an overview of Ansible Galaxy
              also real-world experience from James on how roles are being used in production.

        - name: Learn Ansible in 5 minutes
          presentation:
            by: Jonatan Bjork
            document: 02-FIXME.pdf
            abstract: |
              former organiser of Ansible Oxford and DevOps Oxford, will
              show us the fastest way to get your colleagues from zero to playbook.

        - name: Ansible Templates
          presentation:
            by: Jiri Tyr
            document: 03-Templating-in-Ansible.pptx
            abstract: |
              Jiri Tyr is back on stage, this time demonstrating the power and flexibility of
              Jinja 2 templates.

        - name: Secret Management in Ansible
          presentation:
            by: Dimple Dalby
            document: 04-Ansible-vault-and-Consul.pptx
            abstract: |
              Dimple Dalby will show us how to deal with secrets in Ansible, including some
              best practices. We will also see how Consul can be used as a vault backend.
