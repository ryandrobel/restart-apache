# restart-apache
A simple Bash script for reloading Apache vhost configs.
```
In the terminal
cd ~
cd restart apache
sudo ./re.sh
enter password
```
## Usage
Clone the repository or download the latest release. 

From a command-line call re.sh with two arguments.
1. The vhost configuration
1. The service directive {restart|reload}
```sh
./re.sh 000* restart
enter passowrd
sudo systemctl reload apache2
```

<!-- #don't forget to restart apache -->