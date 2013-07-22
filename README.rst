HP Cloud Auth Plugin for OpenStack Clients
==========================================

This is a plugin for OpenStack Clients which provides client support for
HP Cloud authentication extensions to OpenStack. It also provide default auth
URL support.

Supernova Configuration
-----------------------
If you use [supernova](https://github.com/major/supernova), the following
variables are required:

    [hpcloud]
    OS_USERNAME = API Access Key
    OS_PASSWORD = API Secret Key
    OS_TENANT_NAME = Project Name
    OS_AUTH_SYSTEM = "hpcloud"

Optionally:
    OS_REGION_NAME = az-3.region-a.geo-1
