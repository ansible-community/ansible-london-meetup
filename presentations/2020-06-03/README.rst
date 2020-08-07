.. code-block:: yaml

    - name: Ansible Meetup
      hosts: G-Research
      vars:
        date: 2020-06-03
        link: https://www.meetup.com/Ansible-London/events/270746783/
        sponsors:
          - G-Research
      talks:
        - name: The Evolution of Ansible Tower at Gamesys
          presentation:
            by: Mike McCarthy
            document: FIXME.pdf
            abstract: |
                We've been using Ansible Tower at Gamesys now for many years,
                and it has become the de facto standard for how we deploy our
                artefacts across environments. In this talk we'll share why we
                use Tower, what works well for us, and what we've learnt over
                the last few years that has led us to the setup we have now.
                And a quick peek at where we might go with it!
            recording: https://www.youtube.com/watch?v=T-1mH72WGzI
        - name: Using pre-commit to ease linting Ansible code repos
          presentation:
            by: Sorin Sbarnea
            document: FIXME.pdf
            abstract: |
                How to introduce linting gradually on old code repositories
                and ease its maintenance. While it touches ansible-lint
                is not limited to it and it covers use of multiple linters via pre-commit.
            recording: https://www.youtube.com/watch?v=oQwUyOXR0Vg
