ansible-role-nginx
=============

Install Nginx.

### Variables:

| name | type | description |
|------|------|-------------|
| `nginx_version` | string | Nginx version (default: `stable`, valid options are: `stable` or `development`) |
| `nginx_delete_default_site` | boolean | Whether or not to delete the default Nginx site (default: `False`) |


**TODO**

* supervisor
* tests
* travis config
* debian
* rhel
