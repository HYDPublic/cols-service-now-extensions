# Colin's ALM Corner ServiceNow Azure DevOps Extensions

This extension is for ServiceNow extensions and includes:
- Service Now Release Gate

## Service Now Release Gate

|Phase|Badge|
|---|---
|Build|![Build Status](https://colinsalmcorner.visualstudio.com/MarketPlace/_apis/build/status/ServiceNow%20Extensions)|
|Beta Release|![Release Status](https://colinsalmcorner.vsrm.visualstudio.com/_apis/public/Release/badge/34532943-412e-4dac-b314-a87833e22dd8/4/6)|
|Public Release|![Release Status](https://colinsalmcorner.vsrm.visualstudio.com/_apis/public/Release/badge/34532943-412e-4dac-b314-a87833e22dd8/4/7)|

This release gate lets you specify a Change Request number and waits until the change request is in a specified state (default is `Implement`).

To use the gate:
1. Create a `Service Now` service endpoint

    ![Create a Service Now endpoint](https://github.com/colindembovsky/cols-service-now-extensions/raw/master/media/snow_endpoint.png "Create a Service Now endpoint")

1. Create a gate, specifying the Service Now endpoint, the Change Request number (this can be a variable) and the state to check for:

    ![Create a Change Request gate](https://github.com/colindembovsky/cols-service-now-extensions/raw/master/media/snow_gate.png "Create a Service Now Change Request gate")