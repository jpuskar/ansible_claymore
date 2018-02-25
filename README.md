Role Name
=========

Configures AMDGPU-PRO, ROCm, and Claymore for Ubuntu.


Requirements
------------

- Python installed.
- Pre-stage amdgpu-pro-17.40-483984.tar.xz at /root.
- Secure-boot must be disabled.


Role Variables
--------------

- wallet_address
- wallet_email
- miner_name


Misc
----

Show cpu clock speed (amd) on GPU #6.
```/sys/kernel/debug/dri/6/amdgpu_pm_info```


TODO
----

- LUKS
- DoD STIGS
- ssh lockdown & keys
- apparmor
- systemd unit file for claymore


License
-------

GPL


Author Information
------------------

https://github.com/jpuskar/ansible_claymore
