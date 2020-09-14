.. code-block:: yaml

- name: Ansible Meetup
  hosts: G-Research
  vars:
    date: 2020-09-10
    link: https://www.meetup.com/Ansible-London/events/272502539/
    sponsors:
      - G-Research
  talks:
    - name: Ansible Inventory Plugins
      presentation:
        by: Jiri Tyr
        document: [Ansible Inventory Plugins](Ansible Inventory Plugins.pdf)
        abstract: |
          In one of the past meetups, we have learned how to create a Dynamic
          Inventory Script. Ansible has evolved since and scripts were replaced
          by plugins. This talk will explore the differences between the
          Dynamic Inventory Script and the Inventory Plugin and will show how
          to write your own Inventory Plugin.
        recording: null

    - name: Verification and Validation Testing with Ansible and Goss 
      presentation:
        by: Colin Cowlan
        document: [ansible-goss-testing](ansible-goss-testing.pdf)
        abstract: |
          Goss is a YAML based serverspec alternative tool for validating a 
          server’s configuration. GOSS is exceptionally easy to deploy an use, 
          this presentation shows how you can use Ansible and GOSS together 
          to verify and validate your deployments.
        recording: null
        links: https://github.com/belfast77/ansible-goss-testing
