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
        document: 2024-09-ansible-pilot-from-zero-to-hero.pdf
        abstract: |
            How I share my knowledge and create an Ansible Community by sharing real code examples throw
            videos and blog articles. Sharing some real use cases, each article shows the status of the system
            before and after running the code. The Ansible Pilot website has 150K views/month, and the YouTube channel
            has 26K views/month.
        website: https://www.ansiblepilot.com/
    - name: What's new about Ansible DevTools
      presentation:
        by: Sorin Sbarnea
        document: 2024-09-ansible-devtools.pdf
        abstract: |
            Sorin will give an update and demo on what's been happening in Ansible Development Tooling.
            Including Using GitHub Actions to test and publish Ansible collections
      website: https://ansible.readthedocs.io/projects/dev-tools/
    - name: Ansible Community Update
      presentation:
        by: Don Naro
        document: 2024-09-ansible-community-team.pdf
        abstract: |
            Several members of the Ansible Community team from Red Hat are in town and will be giving a short update on initiatives to support contributors and foster the community. We'll be discussing the Ansible Forum, the "lift and shift" effort to create a standalone documentation project, as well as other work going on such as package releases and the collection inclusion process.
      website:
        - https://forum.ansible.com/
        - https://docs.ansible.com/
        - https://github.com/ansible/ansible-documentation/
        - https://ansible.readthedocs.io/
```
