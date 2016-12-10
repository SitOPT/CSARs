# CSARs
Contains the CSARs for SitOPT

## RMP.csar

Contains the topology and implementation for the [Resource-Management-Platform](https://github.com/SitOPT/Resource-Management-Platform).

## SitTempModTool.csar

Contains the topology and implementation for the [Situation-Template-Modeling-Tool](https://github.com/SitOPT/Situation-Template-Modeling-Tool).

## Variables

| Variable | Description |
|------------------------|-----------------------------------------------------------|
| VMPublicKey | Public Key OpenTOSCA uses |
| VMPrivateKey | Private Key OpenTOSCA uses to connect to the VM |
| VMKeyPairName | Key Pair that is used to create the VM on OpenStack |
| VMUserName | Username OpenTOSCA uses to connect to the VM |
| VMUserPassword | Password for the user OpenTOSCA uses to connect to the VM |
| HypervisorEndpoint | URL where the OpenStack-instance is running |
| HypervisorUserName | User that is used to connect to OpenStack |
| HypervisorUserPassword | Password that is used to connect to OpenStack |
| HypervisorTenantID | Project name which the VM should belong to |
