### Infrastructure provisioning automation ###

Prerequirements:
1. Download code
2. Install terraform, kubectl, helm and gcloud
3. Run `gcloud auth login <your.email@whatever.com>`
4. Run `gcloud auth application-default login`

#### Provision the infrastructure ####
```
$ make provision
```

#### Deprovision the infrastructure ####
```
$ make deprovision
```
