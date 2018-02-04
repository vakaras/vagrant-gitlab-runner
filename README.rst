Install ``vagrant-disksize`` plugin::

    vagrant plugin install vagrant-disksize

Start a virtual machine::

    vagrant up

Log into the machine and register the GitLab runner::

    vagrant ssh
    sudo gitlab-runner register
