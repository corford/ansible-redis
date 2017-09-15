# Redis Ansible Role
Ansible role for redis based on geerlingguy but adds support for using Chris Lea's PPA repo when provisioning an Ubuntu machine

## Variable additions (shown with their defaults)

redis_use_custom_ubuntu_repo: yes
redis_ubuntu_apt_signing_key_id: 1024R/136221EE520DDFAF0A905689B9316A7BC7917B12
redis_ubuntu_apt_repo: http://ppa.launchpad.net/chris-lea/redis-server/ubuntu

## Dependencies

None.

## License

MIT / BSD
