.. code-block:: yaml

    - name: Ansible Meetup
      hosts: Sainsbury's Holborn Office
      vars:
        date: 2017-11-07
        link: https://www.meetup.com/Ansible-London/events/244150258/
        sponsors:
          - Red Hat for Pizza
          - Sainsbury's for beverages
      tasks:
        - name: Introducing the AWX Project
          presentation:
            by: Chris Houseknecht, Ansible by Red Hat
            abstract: |
              You may have heard about the new open source AWX Project, which is the upstream for Ansible Tower.
              What is it, and why do you want it? Chris Houseknecht of Ansible will take us through a demo
              in which he'll cover installation, basic usage, and a bit of architecture.

        - name: Developing modules
          presentation:
            by: Jiri Tyr
            document: 02-Development-of-Ansible-Modules.pptx
            abstract: |
              Although Ansible ships with 1,400+ modules, sometimes you may need a custom module,
              this talk will show you can develop Ansible modules, as well as the process to get
              them merged upstream
