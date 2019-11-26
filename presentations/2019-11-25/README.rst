.. code-block:: yaml

    - name: Ansible Meetup
      hosts: KPMG
      vars:
        date: 2019-11-25
        link: https://www.meetup.com/Ansible-London/events/265681961/
        sponsors:
          - KPMG
      talks:
        - name: Provisioning VMs on VMware ESXi with Ansible
          presentation:
            by: Jiri Tyr
            document:
            abstract: |
              How to use Ansible to build VM templates, how to upload them to vCenter and how to build and rebuild VMs from such template.
            recording:
        - name: The power of local facts
          presentation:
            by: McCarthy
            document: The_power_of_local_facts.pdf
            abstract: |
              Cover how you can set up and use local server facts to act like an ENC (external node classifier)
              and provide fact variables to ansible to allow location, environment & role specific information to customise our ansible runs.
            recording:
        - name: Continuous testing of ansible roles with docker
          presentation:
            by: Vladimir Tiukhtin - KPMG
            document:
            abstract: |
              - Why do we need continuous testing
              - Why docker
              - Is systemd a problem
              - Integrating all together
            recording:

