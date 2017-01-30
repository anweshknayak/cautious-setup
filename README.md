# cautious-setup

Node : effin proxy | alternate(TCP-VPN)

tcp-vpn 
* --BEGIN-- till --END-- save in a .ca file
* setup necessary libraries for the same

proxy-node 
* set url without " "
* add node registery
http://stackoverflow.com/questions/7559648/is-there-a-way-to-make-npm-install-the-command-to-work-behind-proxy

bower 
* sudo chown -R ~/.npm|~/.config
to do :
dotfiles config.

{
  "directory": "bower_components",
  "proxy":"http://172.31.1.3:8080",
  "https-proxy":"http://172.31.1.3:8080"
}
