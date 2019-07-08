gentoo-buildserver
=========

Configure a gentoo multiprofile build server based on chroot and configure lighttpd to expose bin packages

Requirements
------------

None.

Role Variables
--------------

    build_profile: example
    build_dir: /var/builds
    download_latest_stage3: true
    number_of_make_jobs: 12

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
        - { role: gentoo-buildserver, build_dir: /var/builds, build_profile: example, download_latest_stage3: true, number_of_make_jobs: 12}

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
