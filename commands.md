# Check keepalive
sysctl net.ipv4.tcp_keepalive_time

#Check retries
sysctl net.ipv4.tcp_keepalive_probes

#Check intervals
sysctl net.ipv4.tcp_keepalive_intvl

# Enable keepalive 
sudo sysctl -w net.ipv4.tcp_keepalive_time=60
