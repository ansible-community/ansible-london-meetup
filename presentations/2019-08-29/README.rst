.. code-block:: yaml

    - name: Ansible Meetup
      hosts: Sainsbury's Holborn Office
      vars:
        date: 2019-08-29
        link: https://www.meetup.com/Ansible-London/events/263354480/
        sponsors:
          - Venue Sainsbury's, they are hiring, checkout https://tinyurl.com/joinusjs
          - Drinks and pizza, F5
      talks:
        - name: Ansible to bridge the gap between DevOps and Infrastructure
          presentation:
            by: Bart Van Bos - F5
            document: ./DevOps-Pipelines.to.bridge.the.Gap-BartVanBos.pdf
            abstract: |
              Many companies try to bridge the cultural/knowledge gap between development and operational 
              infrastructure teams. As most infrastructure providers today, are offering Ansible support 
              for their (HW or SW) based solutions, there is an opportunity to bridge that gap, using 
              common tools (Ansible) and processes (CI/CD pipelines). F5 Networks offers imperative and 
              declarative REST API’s in order to fit application delivery needs.
            recording:
        - name: 33% higher profit; 300% more innovation; 125% less burnout - Positive Psychology with Ansible
          presentation:
            by: James Freeman - Quru
            document: ./James Freeman - Positive Psychology with Ansible.pdf
            abstract: |
              Organisations that implement Positive Psychology have shown demonstrable improvements in levels of innovation and profitability
              alongside improved employee well-being. Recent studies have shown that technology workers are suffering a crisis in their 
              emotional and mental well-being, and this talk explores the topics of Positive Psychology and Authentic Happiness, and discusses
              how Ansible directly supports these.
            recording:
        - name: How to make Systems Administrator life easy using Ansible
          presentation:
            by: Deepak Kumar Ramanujam
            document:
            abstract:
            recording:
        - name: General updates
          presentation:
            abstract:
              - PR review days days 3rd & 19th Sept, got some free time, join us online http://bit.ly/ansibleprs
              - AnsibleFest Atlanta https://ansible.com/ansiblefest
              
