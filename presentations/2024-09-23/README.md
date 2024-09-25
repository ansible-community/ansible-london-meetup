```yaml
- name: Ansible Meetup
  hosts: Dell
  vars:
    date: 2024-09-23
    link: https://www.meetup.com/ansible-london/events/303113460/
    sponsors:
      - Dell
  talks:
    - name: From Zero to Hero: How to build the Ansible Pilot Community
      presentation:
        by: Luca Berton
        document: [How to build the Ansible Pilot Community](fixme.pdf)
        abstract: |
            How I share my knowledge and create an Ansible Community by sharing real code examples throw
            videos and blog articles. Sharing some real use cases, each article shows the status of the system
            before and after running the code. The Ansible Pilot website has 150K views/month, and the YouTube channel
            has 26K views/month.
        website: https://www.ansiblepilot.com/
    - name: What's new about Ansible DevTools
      presentation:
        by: Sorin Sbarnea
        document: [DevTools](2024-09-ansible-devtools.pdf)
        abstract: |
            Sorin will give an update and demo on what's been happening in Ansible Development Tooling.
            Including Using GitHub Actions to test and publish Ansible collections
      website: https://ansible.readthedocs.io/projects/dev-tools/
    - name: Ansible Community Update
      presentation:
        by: Don Naro
        document: [Ansible Community](fixme.pdf)
        abstract: |
            Most of the Ansible Community team from Red Hat are in town, and will be giving a short update on
            the recent initiatives including The Ansible Forum and the move to Read The Docs for Ansible upstream
            projects.
      website:
        - https://forum.ansible.com/
        - https://ansible.readthedocs.io/
```
