// Requirements

// You need to have the following installed
// 1. virtualbox
// 2. vagrant
// 3. anisble 

// To have the playbook running correctly you need to;

// 1. spin up a server using vagrant, add your ssh public key it the authorised_keys file. 
// you should be able to login to your server by running ssh vagrant@<server_ip_addr>

// 2. replace your servers ip with ip in the host file under [node1]

// run your playbook with the command *ansible-playbook <the playbook> -u vagrant -i hosts*
