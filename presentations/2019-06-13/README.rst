.. code-block:: yaml

    - name: Ansible Meetup
      hosts: Sainsbury's Holborn Office
      vars:
        date: 2019-06-13
        link: https://www.meetup.com/Ansible-London/events/260638878/
        sponsors:
          - Venue Sainsbury's, they are hiring, checkout https://tinyurl.com/joinusjs
          - Drinks and pizza, NetApp
      talks:
        - name: Infrastructure as Code with Ansible + NetApp
          presentation:
            by: Tom Harris - NetApp
            document:
            abstract: |
               NetApp is proud to be one of only six Red Hat Certified Supported Module Vendors,
               this session shows how Ansible modules enable our customers
               to automate and standardize deployments across clouds.
        - name:  Our learnings since we started using Ansible @ FT
          presentation:
            by: Nayana Shetty - FT
            document:
            abstract: |
              We started using ansible actively in my team toward the end of 2017 beginning of 2018.
              We are now answering questions on what is our standards around creating new ansible modules and playbooks,
              how do we test in a sensible and sustainable way.
              It would be interesting to share our story and what we would do differently if we started over this again.
        - name: Self-healing applications with Ansible
          presentation:
            by: Jürgen Etzlstorfer - Dynatrace
            document:
            abstract: |
             In this session we will explore how to leverage Ansible as automation platform to automate remediation tasks.
             Upon of this, we will learn what is needed to build your own remediation workflow including monitoring,
             automation and orchestration tools to setup and control your remediation actions.
        - name: How does Ansible's agentless architecture work?
          presentation:
            by: Jiri Tyr
            document:
            abstract: |
              This talk will discuss how Ansible packs and propagates its code to the remote machine and how it runs it there.
