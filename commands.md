# ============================================
# TCP Keep-Alive Commands
# ============================================

# --- Check current settings ---
sysctl net.ipv4.tcp_keepalive_time

sysctl net.ipv4.tcp_keepalive_probes

sysctl net.ipv4.tcp_keepalive_intvl

# --- Apply new settings (requires root) ---
sysctl -w net.ipv4.tcp_keepalive_time=60

sysctl -w net.ipv4.tcp_keepalive_probes=5

sysctl -w net.ipv4.tcp_keepalive_intvl=10
