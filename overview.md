# McDonalds Private Azure DevOps Extensions

This extension is for several _private_ McDonalds extensions:
- Service Now Release Gate

## Service Now Release Gate
This release gate lets you specify a Change Request number and waits until the change request is in a specified state (default is `Implement`).

To use the gate:
1. Create a `Service Now` service endpoint

    ![Create a Service Nnow endpoint](media/snow_endpoint.png "Create a Service Now endpoint")

1. Create a gate, specifying the Service Now endpoint, the Change Request number (this can be a variable) and the state to check for:

    ![Create a Change Request gate](media/snow_gate.png "Create a Service Now Change Request gate")