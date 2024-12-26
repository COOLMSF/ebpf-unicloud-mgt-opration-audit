# Intro

audit user opration in fast way

# install

1. run `bash install.sh`

2. run `sudo systemctl daemon-reload`

3. run `sudo systemctl enable audit-bpftrace.service`

4. run `sudo systemctl start audit-bpftrace.service`

5. run `sudo systemctl status audit-bpftrace.service`
