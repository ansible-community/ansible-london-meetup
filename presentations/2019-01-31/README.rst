.. code-block:: yaml

    - name: Ansible Meetup
      hosts: Sainsbury's Holborn Office
      vars:
        date: 2019-01-31
        link: https://www.meetup.com/Ansible-London/events/257896565/
        sponsors:
          - Red Hat for beiverages and pizza
          - Sainsbury's for the venue
      tasks:
        - name: An Ansible Developer and Ecosystem Story
          presentation:
            by: Tim Appnel, Senior Product Manager, Ansible
            document: FIXME
            abstract: |
              This presentation is about what we are observing, thinking about and steering
              Ansible over the coming years. This will be rolled out incrementally over time
              allowing for as gradual transition and testing period as we can. We still have
              a long ways to go and a lot of details to work out, but we want to be open and
              transparent about this. An introduction to Ansible roles and an overview of
              Ansible Galaxy also real-world experience from James on how roles are being
              used in production.
            links:
              - github.com/ansible/galaxy
              - github.com/ansible/mazer
              - github.com/ansible/ansible-lint
              - github.com/ansible/molecule
              - galaxy-dev.ansible.com
              - #ansible-galaxy on IRC
              - #ansible-molecule on IRC

        - name: How I use Ansible to save me 30 minutes a day
          presentation:
            by: Roger Perkin
            document: https://github.com/rogerperkin/ansible-meetup
            abstract: |
              As a network consultant I am always staging new environments and working on
              new networks every week. Ansible makes my initial audit of a new customer
              network very easy, and has also saved me hours and hours when staging
              new environments.

        - name: Bringing Ansible to an existing ops infrastructure
          presentation:
            by: Michael Kaye, matrix.org
            document: Introducing Ansible to matrix-final.pdf
            abstract: |
              Discussing approaches I've taken to adopt Ansible within matrix.org,
              describing where we started, what worked, what ran into problems. I'll
              cover four or five strategies I tried.

        - name: Automate Kubernetes Workloads with Ansible
          presentation:
            by: Michael Hrivnak, Red Hat
            document: automate-k8s-workloads-ansible.pdf
            abstract: |
              Ansible's k8s module makes it easier than ever to automate a Kubernetes
              cluster, even for someone who has little Ansible experience. This talk introduces
              the k8s module and shows how it can be used to define and distribute an
              application for self-service provisioning. We will conclude by learning
              how to achieve day-two management by making an Ansible-based Operator.
            links:
              - http://automationbroker.io/
              - https://github.com/operator-framework/operator-sdk/
              - https://learn.openshift.com/operatorframework/
