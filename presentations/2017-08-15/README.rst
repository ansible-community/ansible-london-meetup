.. code-block:: yaml

    - name: Ansible Meetup
      hosts: Sainsbury's Holborn Office
      vars:
        date: 2017-08-15
        link: https://www.meetup.com/Ansible-London/events/241643732/
        videos: https://www.youtube.com/watch?v=aaHKZBekXPw
        sponsors:
          - Red Hat for Pizza
          - Sainsbury's for beverages
      tasks:
        - name: Provisioning iOS CI servers with Ansible
          presentation:
            by: Shashikant Jagtap
            slides: https://www.slideshare.net/Shashikant86/provisioning-ios-ci-server-with-ansible
            video: https://www.youtube.com/watch?v=aaHKZBekXPw&t=378s
            abstract: |
              Learn how Ansible can be used to provision Mac Mini servers for iOS
              continuous integration and continuous deployment (CI/CD).

        - name: Dynamic cloud environments with Ansible
          presentation:
            by: Zsolt Kulcsar
            slides: https://github.com/zskulcsar/ansible-dynamic-cloud-envs-talk
            video: https://www.youtube.com/watch?v=aaHKZBekXPw&t=2330s
            abstract: |
              Some best practices around Ansible and dynamic cloud environment using AWS,
              such as resource tagging, groups, auto scaling, pull vs push.

        - name: Overcoming problems of the standard Ansible inventory file
          presentation:
            by: Jiri Tyr
            slides: https://www.slideshare.net/jtyr/overcoming-problems-of-the-standard-ansible-inventory-file
            video: https://www.youtube.com/watch?v=aaHKZBekXPw&t=4127s
            abstract: |
              Discussion and demo around how to use dynamic inventory as a way of overcoming
              the issues of flat inventory files and group_vars.

        - name: Lambda Microsservice Deployment direct from Ansible
          presentation:
            by: Michael De La Rue
            slides: https://slogme.wordpress.com/2017/08/15/notes-for-ansible-aws-talk-2017-08-28/
            video: https://www.youtube.com/watch?v=aaHKZBekXPw&t=5709s
            abstract: |
              How Ansible can deploy microservices, and why that's useful, rather than using
              Ansible to drive Serverless.
