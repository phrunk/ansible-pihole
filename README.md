# ansible-pihole
Minimalist Ansible role to install a pihole on a already running raspian installation.  
Mostly inspired by: https://github.com/gsemet/ansible-rpi-pihole

See [defaults.yml](defaults/main.yml) for available variables.

### Hint
To be able to successfully login, you have to initially reset the webpassword with

```bash
pihole -a -p
```

Then set the `pihole_webinterface_password` variable in your vars file.
