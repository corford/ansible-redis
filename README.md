# Ansible Role: Redis

Ansible redis role (based on geerlingguy) with support for using a custom PPA repo when provisioning Ubuntu machines.

## Variable additions (shown with their defaults)

```
redis_use_custom_ubuntu_repo: yes
redis_ubuntu_apt_signing_key_id: 1024R/136221EE520DDFAF0A905689B9316A7BC7917B12
redis_ubuntu_apt_repo: http://ppa.launchpad.net/chris-lea/redis-server/ubuntu
```

## Dependencies

None

## License

MIT / BSD
