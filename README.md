# ansible-ossec-agent-deploy-ossim
Ansible role to deploy Linux OSSEC agent and connect it to OSSEC server

{{ alientvault_server }} should be set in group_vars to that environment's AV server.

Hosts should be specified in hosts.yml under the [ossec_agent] group (maybe use [unique_hosts]?)
