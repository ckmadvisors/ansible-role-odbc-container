# unixODBC-container

Add UnixODBC to your [Ansible Container](https://github.com/ansible/ansible-container) project. Installs base driver manager, provides flexible framework to configure custom drivers with the full power of Ansible, and sets up system-wide DSN entries.


```
# Set the working directory to your Ansible Container project root
$ cd myproject

# Install the service
$ ansible-container install marcusianlevine.odbc-container
```

## Requirements

In order to install custom drivers and DSN snippets, you must provide `.ini` snippets of the form found in `snippets`.

Any custom driver binaries or installers should be referenced either by absolute path, or relative to the location where your playbook will be run.

## Role Variables

## License

BSD

## Author Information

Written by Marcus Levine and Marshall van Loon for CKM Advisors