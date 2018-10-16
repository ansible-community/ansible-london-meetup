.. code-block:: yaml

    - name: Ansible Meetup
      hosts: Sainsbury's Holborn Office
      vars:
        date: 2018-10-15
        link: https://www.meetup.com/Ansible-London/events/254403376/
        sponsors:
          - Cumulus Networks for drinks and pizza
          - Sainsbury's for venue. They are hiring Ansible Engineers https://tinyurl.com/joinjs
      tasks:
        - name: If ( Network == Server ) { Magic happens }
          presentation:
            by: Pete, Cumulus Networks
            video: https://youtu.be/1a5mkHWVwCk
            document: 01-Magic-Happens.pdf
            link: https://gitlab.com/packet.ninja/cl-cicd
            abstract: |
              With increasing Linux networking features in the kernel,
              it's now possible to have CI/CD workflows for testing and provisioning the switches in the data centre.

        - name: Jinja2 Filters
          presentation:
            by: Jiri Tyr
            document: no
            link: https://www.slideshare.net/jtyr/jinja-2-filters/
            abstract: |
              Learn how to create Jinja2 filters and how to distribute and use them via an Ansible role

        - name: Integration tests in Ansible
          presentation:
            by: Pavlos Kleanthous
            document:
            abstract: |
              How to use molecule V2 to run integration tests on AWS using Terraform and testinfra
            link:
              - https://molecule.readthedocs.io/en/latest/
              - https://groups.google.com/forum/#!topic/molecule-users/O1a_YNAjy-Q
              - https://github.com/willthames/ansible-lint/

        - name: Bonus - GBT - Prompt builder for Bash and ZSH written in GO
          presentation:
            by: Jiri Tyr
            link: https://github.com/jtyr/gbt
            document: no
            abstract: |
              Thanks Jiri for sharing this prompt builder with us as a bonus!

        - name: Ansible updates
          presentation:
            by: John "gundalow" Barker
            abstract: |
              Ansible 2.7.0 has been released https://groups.google.com/forum/#!topic/ansible-announce/fx7nxwL4hMM
              Join the Ansible Community Working Groups, https://github.com/ansible/community/#groups
              AnsibleFest videos will be release soon on https://ansible.com/videos
