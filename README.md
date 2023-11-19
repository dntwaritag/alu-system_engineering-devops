This repository contains scripts and configuration files related to SSH setup and client-server connections. Below is an overview of the tasks accomplished:

Task 0: Use a private key

Description: Establishes an SSH connection to a server using the specified private key.
File: 0-use_a_private_key
Task 1: Create an SSH key pair

Description: Generates an RSA key pair with specified parameters.
File: 1-create_ssh_key_pair
Task 2: Client configuration file

Description: Configures the local SSH client to connect to a server without using a password.
File: 2-ssh_config
Task 3: Let me in!

Description: Adds an SSH public key to the server to allow connection using the ubuntu user.
Directory: ssh
Task 4: Client configuration file (w/ Puppet)

Description: Uses Puppet to configure the SSH client file for passwordless authentication.
File: 100-puppet_ssh_config.pp
