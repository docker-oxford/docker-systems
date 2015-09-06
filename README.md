# docker-systems
Configure systems to run docker

## Test

To test the playbook run

    ansible-playbook test.yml -e "os_choice=<os>"

where os can (for the moment) be:

    ubuntu_precise
    ubuntu_trusty
