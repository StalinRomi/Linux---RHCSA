## Tuning

Its a Linux feature that **monitors a system, & optimizes its performances** under certain workloads.

### Profile is set of rules.

It defines certain system parameters, such as **disk settings, Kernel parameters, network optimization**, settings, etc.

tuned-adm list - To check available profiles.

### **tuned-adm profile profile-name** - To set a new Profile

## Network Service

It runs at the application layer to provide some form of service over a network. Our client's will contact the service for access.
Eg. Apache Web Server

### To start -sudo systemctl start service-name

### To stop - sudo systemctl stop service-name

### To check - systemctl status service-name / sysemctl is-active service-name
