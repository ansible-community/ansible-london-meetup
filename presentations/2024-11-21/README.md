- name: Ansible Meetup
  hosts: Dell
  vars:
    date: 2024-11-21
    link: https://www.meetup.com/ansible-london/events/303935960/
    sponsors:
      - Dell
  talks:
    - name: Let's use RAG for Ansible coding and say goodbye to tedious tasks
      presentation:
        by: Benoît Fabre
        document: FIXME.pdf
        abstract: |
            Writing comprehensive documentation and extensive Molecule test cases is essential when buildin
            quality Ansible collections, yet these elements are often overlooked by developers. In this talk,
            we’ll dive into our experiments with Retrieval-Augmented Generation (RAG) techniques, where we injected
            custom Ansible repositories as context to LLMs and evaluated the accuracy of the output.
            Join us as we share insights and findings on how RAG can help you as Ansible developer.
    - name: Infrastructure as Code - VPS provisioning and configuration on Hetzner Cloud
      presentation:
        by: Daniel Brennand
        document: FIXME.pdf
        abstract: |
            This talk will a demo on provisioning a VPS using Ansible on Hetzner Cloud and running a basic playbook
            to configure the VPS post deployment. The demo will use the dynamic inventory plugin from the
            `hetzner.hcloud` collection too.
    - name: Achieving compliance through ansible-lockdown
      presentation:
        by: Mark Bolwell
        document: FIXME.pdf
        abstract: |
            How to achieve OS baseline compliance with the use of ansible
            Why have we written this
            What compliance can be addressed
            How: A cut back demo showing the steps taken including audit and remediate
