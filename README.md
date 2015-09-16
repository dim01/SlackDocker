# SlackDocker
Slack has changed the way team members communicate. Slack gives developers the ability to easily create custom integrations with 3rd-party APIs to get data out of or into Slack. How about creating a Slack integration service to manage cloud servers with docker machine? Using simple slack commands, the user will be able to create, reboot and delete a dockerized server.

What we should do:
- Authenticate with the Slack App
- Configure a Slack slash Command
- Build a service to receive messages
- Process messages, execute commands on the Docker machine and respond with the outcome to the slack user
