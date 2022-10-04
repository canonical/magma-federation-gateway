# magma-federation-gateway

> **Warning**: This project is under construction


## Overview

Federation Gateway is a Magma service that integrates the MNO core network with Magma by using 
standard 3GPP interfaces to existing MNO components. It acts as a proxy between the Magma AGW and 
the operator's network and facilitates core functions, such as authentication, data plans, policy 
enforcement, and charging to stay uniform between an existing MNO network and the expanded network 
with Magma. For more information about Magma, see the official documentation 
[here](https://magmacore.org/).

This charm bundle makes it easy to deploy the Federation Gateway components in any Kubernetes 
environment, and it has been tested with all major public cloud platforms.

## Usage

```bash
juju deploy magma-feg --trust --channel=edge
```
