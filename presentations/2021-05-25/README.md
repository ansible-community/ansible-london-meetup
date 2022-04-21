```yaml
---
- name: Ansible Meetup
  hosts: G-Research
  vars:
    date: 2021-05-25
    link: https://www.meetup.com/Ansible-London/events/278093392/
    sponsors:
      - G-Research https://www.gresearch.co.uk/join-us/
  talks: 
    - name: Ansible to harden Linux OS
      presentation: 
        by: Alex Marzan
        document: FIXME.pdf
        abstract: |
          FT had been mainly using RHEL 6 until 2017. The way we hardened them to be inline with our Operating System
          standards was by creating RPMs for each component example RPMs for LDAP, SUDO, LOGGING, etc. In 2017 when we
          had more and more teams started moving to use Amazon Linux, we decided to not use RPMs to harden our severs
          but instead create Ansible modules. We bundle these into an ansible-playbook that can be pulled from a central
          location and it runs on servers at regular intervals. So an engineer in the FT who wants to build a Amazon
          Linux server would get the latest/any ami from Amazon and then runs the ansible playbook as part of the User Data
          while building the server. In this talk I would like to go into the details of how these modules work, what kind of
          testing we do, the pipeline we have when we want to make a new release and the benefits we have been seeing due
          to this approach to harden servers.

        recording: FIXME YouTube
        links:
          - FIXME
    - name: Deploying PHP applications with Ansible, Ansible Vault and Ansistrano
      presentation: 
        by: Oliver Davies
        document: Deploying-PHP-Ansistrano.pdf
        abstract: |
          Great! You’ve built your website, and now you just need to deploy it. There are various ways that this could be done
          from (S)FTP, to SCP and rsync, to running commands like git pull and composer install directly on the server which is not ideal.
          As well provisioning and maintaining your server configuration and running commands, you can also use Ansible to deploy your
          PHP application - leveraging relevant Ansible modules such as Git and Composer, custom Ansible roles, Ansible Vault for
          managing secrets, and features such as idempotency out of the box to build a simple deployment playbook.
          We can then extend that and make it more robust by adding Ansistrano - a port of Capistrano - which adds extra features such
          as storing multiple builds for each project and the ability to roll-back if needed, customising your build steps using
          built-in hooks, multi-stage environments and more.
          I've been using Ansible and Ansistrano to deploy a variety of PHP projects - including Drupal 7 & 8, Symfony, Laravel and Sculpin,
          as well as basic HTML websites, and found it to be very flexible and easy to install and use, and by the end of this talk we will
          have a fully working deployment playbook, deploying real code onto a real server.
          Note that this is focused on PHP applications and Drupal in particular, but applies to any language and CMS or framework.

        recording: FIXME YouTube
        links:
          - https://ansistrano.com
          - https://twitter.com/opdavies
          - https://www.oliverdavies.uk/talks/deploying-php-applications-ansible-ansible-vault-ansistrano
          - https:/symfonycasts.com/screencast/ansistrano
    - name: The Ansible Playbook Generator
      presentation: 
        by: Dennis McCarthy
        document: FIXME.pdf
        abstract: |
          I use Ansible a lot for work and fun and thought, wouldn't it be nice if I could tell Ansible what I wanted to do, and it
          would just do it. So that's what the Ansible Playbook Generator does. You give it a list of what you want to create a playbook
          for, then you run the playbook generator and it creates all the playbooks you need. Currently, it supports packages, services,
          templates (including handlers) and sets up group_vars too. You can take the playbooks it generates, make changes and watch it
          update the server(s) with your new changes.
        recording: FIXME YouTube
        links:
          - https://github.com/dmccuk/AnsiblePlaybookGenerator

```
