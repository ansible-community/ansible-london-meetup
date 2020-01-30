.. code-block:: yaml

    - name: Ansible Meetup
      hosts: G-Research
      vars:
        date: 2020-01-29
        link: https://www.meetup.com/Ansible-London/events/267275106/
        sponsors:
          - G-Research
      talks:
        - name: Ansible Callback Plugins
          presentation:
            by: Jiri Tyr
            document: Ansible Callback Plugins.pdf
            abstract: |
                Ansible is extensible via various plugins. One of them are
                Callback Plugins which allow to customize the output displayed
                during Ansible run. This talk shows how to use Callback Plugins
                and how to develop a new one.
            recording:
