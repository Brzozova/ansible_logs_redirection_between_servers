# Rsyslog logs redirection between servers

The server X has a big disk, so we can use it as the destination for rsyslog, where logs from network devices (Mikrotiks) will be stored. We need to prepare rsyslog on server X and connect all network devices.

Two remote servers: one act as router with Mikrotik, second is random server X with web application.

Connection: TCP/UDP

