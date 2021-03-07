# DiscordNetworkChatBot
Ansible playbooks that chat with Discord using Ansible, Genie/pyATS, and the Discord webhooks that send network state information as a Discord message!

## Prerequisites:
Ansible
Genie
Discord Server with Channel and Webhook Integration

### Instructions
Update the following:
hosts - update your target switch(s)
playbooks - update your target (host); Webhook URL (URI, URL), Username (URI, Body)
Save and run playbook 
Answer prompts for device username and password with privliedge 15 on the CLI
Confirm receipt of chat in Discord channel 