# Ansible role:
install OVPN clients on Ubuntu 'xenial' hosts only

List client hosts:
<pre>
/hosts.txt
</pre>
Change user in:
<pre>
/group_vars/ovpn_clients
</pre>
Change OVPN server IP and PORT in file:
<pre>
/roles/deploy_ovpn_client/defaults/main.yml
</pre>
Edit Jinja template to change SERVER/CLIENT keys:
<pre>
/roles/deploy_ovpn_client/templates/etc/openvpn/client.conf.j2
</pre>
