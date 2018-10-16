.. code-block:: yaml

    - name: Ansible Meetup
      hosts: Sainsbury's Holborn Office
      vars:
        date: 2018-10-15
        link: https://www.meetup.com/Ansible-London/events/254403376/
        sponsors:
          - Cumulus Networks for drinks and pizza
      tasks:
        - name: If ( Network == Server ) { Magic happens }
          presentation:
            by: Pete, F5 Networks
            document: 01-Magic-Happens.pdf
            abstract: |
              With increasing Linux networking features in the kernel,
              it's now possible to have CI/CD workflows for testing and provisioning the switches in the data centre.

        - name: Jinja2 Filters
          presentation:
            by: Jiri Tyr
            document:
            abstract: |
              Learn how to create Jinja2 filters and how to distribute and use them via an Ansible role

        - name: Integration tests in Ansible
          presentation:
            by: Pavlos Kleanthous
            document:
            abstract: |
              How to use molecule V2 to run integration tests on AWS using Terraform and testinfra

