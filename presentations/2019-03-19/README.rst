.. code-block:: yaml

    - name: Ansible Meetup
      hosts: Sainsbury's Holborn Office
      vars:
        date: 2019-03-1931
        link: https://www.meetup.com/Ansible-London/events/258726000/
        sponsors:
          - Venue Sainsbury's, they are hiring, checkout https://tinyurl.com/joinjs
          - Drinks and pizza, G-Research, they are hiring, checkout https://gresearch.co.uk
      talks:
        - name: An overview of how G-Research use Ansible for infrastructure automation
          presentation:
            by: Luke Griffith, G-Research
            document: FIXME
            abstract: |
              G-Research use Ansible to automate infrastructure and perform orchestration
              tasks. I will be talking about the various technologies that we automate
              with Ansible and the different ways we run our playbooks.
            links:
              - https://www.gresearch.co.uk/

        - name: "Variable precedence - Where should I put a variable?"
          presentation:
            by: Jiri Tyr
            document: FIXME
            abstract: |
              We once again welcome Jiri to the stage, this month he's showing us
              everywhere that you could define Ansible variables and how the override
              each other.
           links:
             - https://docs.ansible.com/ansible/latest/user_guide/playbooks_variables.html#variable-precedence-where-should-i-put-a-variable
        - name: Data Deployments with Ansible
          presentation:
            by: Prash Majmudar
            document: FIXME
            abstract: |
              Growth Intelligence is building a platform to help businesses grow faster
              and connect to their customers using AI. We deploy machine learning models
              into a web app backed by data on millions of UK businesses. In this talk,
              I will talk about how we also use Ansible to deploy the data our machine
              learning models rely on and describe how we use Ansible roles and playbooks
              to snapshot/restore Elasticsearch indices into our staging and prod environments.
        - name: How I Provision My Macbook with Ansible
          presentation:
            by: Adam Johnson
            document: 04 How I Provision My MacBook with Ansible.pdf
            abstract: |
              For nearly 5 years I've been installing software and setting up dotfiles on my
              Macbook with Ansible. It has saved me a bunch of time - first in synchronizing
              between home and work laptops, and second when they have to get wiped! I'll
              walk through how it works and hopefully inspire the audience to use Ansible for
              automating their personal IT too.
            links:
              - https://github.com/adamchainz/mac-ansible
         - name: General updates
           abstract:
             - Ansible 2.8 will be released soon, testing welcome https://github.com/ansible/ansible/blob/devel/docs/docsite/rst/roadmap/ROADMAP_2_8.rst
             - Ansible Working Groups https://github.com/ansible/community/wiki


              FIXME: AnsibleFest, 2.8 Dates, Contributor Summits
