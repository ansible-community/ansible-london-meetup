.. code-block:: yaml

    - name: Ansible Meetup
      hosts: Sainsbury's Holborn Office
      vars:
        date: 2018-12-12
        link: https://www.meetup.com/Ansible-London/events/254878934/
        sponsors:
          - Memset for drinks and pizza https://www.memset.com/
          - Sainsbury's for venue. They are hiring Ansible Engineers https://tinyurl.com/joinjs
      tasks:
        - name: Writing your first Ansible module
          presentation:
            by: Simon Weald from Memset
            document: 01-Writing-your-first-Ansible-module.pdf
            link:
            abstract: |
              A relatively high-level view of what goes into writing your first module,
              and some handy hints to help you get your PR merged
        - name: Managing Ansible roles across different environments
          presentation:
            by: Jiri Tyr
            document: no
            link:
            abstract: |
              Demonstrate how to manage Ansible roles across multiple environments (dev, qa, stage, prod).
              How to version it, how to make sure each environment is using only a specific version of the roles
              and how to push versions across all the environments in the meaner of continuous delivery.

        - name: Upgrading the backend database of a £3 billion business website on a Friday Afternoon with Ansible
          presentation:
            by: James Freeman
            document:
            abstract: |
              An unwritten rule in the world of IT Operations is that you never make changes on a Friday afternoon,
              especially not upgrading the backend database for a business e-commerce site contributing a £2 billion revenue.
              Ansible Tower makes the unthinkable thinkable by producing reliable, consistent, repeatable results,
              and removing the possibility of human error from activities.
              One major retailer of sportswear in the UK were so impressed with the performance of Ansible that they felt confident enough to do just this!
            link:
        - name: Ansible updates
          presentation:
            by: John "gundalow" Barker
            document: community-update-Dec-2018.pdf
            abstract: |
              Update on PR review days, next is 19th Dec 2018 in #ansible-community. 
            link:
              - PR Review days https://github.com/ansible/community/issues/407
              - Submit a talk https://github.com/ansible-community/ansible-london-meetup/
              - Community Guide https://docs.ansible.com/ansible/devel/community/
