.. code-block:: yaml

    - name: Ansible Meetup
      hosts: Sainsbury's Holborn Office
      vars:
        date: 2017-10-12
        link: https://www.meetup.com/Ansible-London/events/243310331/
        sponsors:
          - F5 Networks for Pizza
          - Sainsbury's for beverages
      tasks:
        - name: F5
          presentation:
            by: Matthew Prickett, F5 Networks
            abstract: |
              The demo/presentation will comprise of day-0 deployment of web application
              firewalls to instantly protect applications from known web vulnerabilities.

        - name: Role Development
          presentation:
            by: Jiri Tyr
            document: 02-Ansible-Role-Development.pptx
            video: https://www.youtube.com/watch?v=sFuKuHmRuzQ
            abstract: |
              Jiri Tyr returns, this time showing us best practices and some interesting
              patterns for Ansible roles development and will show a way how to test such
              roles locally using Vagrant.

        - name: Ansible Playbooks as checklists
          presentation:
            by: Adam Johnson and Jonathan Burman, Time Out
            document: https://github.com/timeoutdigital/talk-ansible-checklists
            video: https://www.youtube.com/watch?v=O5fj2JFtbis
            abstract: |
              Checklists are great for removing human error from operations, espoused by many famous
              thinkers on systems theory, including Chesley Sullenberger, the airline captain of
              "the miracle on the Hudson" fame.
              We see Ansible playbooks as checklists - ranging from entirely manual playbooks
              composed of prompts to be checked off by an operator, through to fully automated processes.

