```yaml
---
- name: Ansible Meetup
  hosts: virtual
  vars:
    date: 2022-03-19
    link: https://www.meetup.com/Ansible-London/events/284846000/
  talks:
    - name: Intro and welcome
      presentation:
        by: John "gundalow" Barker
        document: https://hackmd.io/@ansible-community/BJaR9V3Vc
        abstract: |
          Welcome and introductions
          The Bullhorn is a weekly newsletter for the Ansible Community
          community-topics allows asynchronous discussion and governance of the Ansible Community
          news-for-maintainers provides Collection Owners timely information on upcoming changes.
        recording: https://youtu.be/VFwqUBlofZg
        links:
          - https://matrix.to/#/#europe:ansible.com
          - https://github.com/ansible/community/wiki/News#the-bullhorn
          - https://github.com/ansible-community/community-topics/issues
          - https://github.com/ansible-collections/news-for-maintainers
          - https://docs.ansible.com/ansible/devel/community/communication.html
    - name: ansible-lint future and its fixing new feature
      presentation:
        by: Sorin Sbarnea
        document: https://sbarnea.com/ss/lint-v6.html
        video: https://www.youtube.com/watch?v=VFwqUBlofZg&t=2570s
        abstract: |
          Introduction to the uplifted status of ansible-lint, its recent changes, and the auto-fixing feature.
          https://github.com/ansible/ansible-lint/discussions/1910
        recording: FIXME YouTube
        links:
          - https://github.com/ansible/ansible-lint
          - https://github.com/ansible/ansible-lint/discussions/1910
    - name: Deploying an OpenStack infrastructure on a single server with Ansible
      presentation:
        by: James Freeman
        document: FIXME.pdf
        video: https://www.youtube.com/watch?v=VFwqUBlofZg&t=4336s
        abstract: |
          This talk will be based on this two part guest blog I wrote for Cumulus Networks,
          https://cumulusnetworks.com/blog/build-an-openstack-ceph-cluster-with-cumulus-networks-in-gns3-part-1/
          In it I will discuss how GNS3 can be used to simulate your entire infrastructure and develop your playbooks, and
          how an entire highly available OpenStack/Ceph infrastructure can be brought up with virtually no manual intervention
          through a combination of cloud-init and Ansible. The talk covers a number of important concepts including whitebox
          switching, network automation with Ansible, building infrastructures, and even how to model an entire infrastructure
          on a single (albeit powerful) machine for a multitude of purposes including testing and developing Ansible playbooks.
        recording: FIXME YouTube
        links:
          - https://cumulusnetworks.com/blog/build-an-openstack-ceph-cluster-with-cumulus-networks-in-gns3-part-1/
    - name: How I migrated from Puppet to Ansible
      presentation:
        by: Dennis McCarthy
        document: puppet_2_ansible.pdf
        video: https://www.youtube.com/watch?v=VFwqUBlofZg&t=2570s
        abstract: |
          This talk is about the journey I started a few month ago to migrate a large code base away from puppet and
          over to Ansible. Highlights include working out an alternative method to hiera (which I feel is actually a
          pretty good part of puppet) and creating an Ansible workflow to act in a similar way to deliver the
          correct configuration to the correct servers. My Ansible knowledge has been pushed to the extreme at
          times but it's only made me see just what Ansible is capable of.h
        recording: FIXME YouTube
        links:
          - FIXME
```
