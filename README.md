# App Connect assets for CP4I Demonstration

This Repo contains multiple App Connect assets (a.k.a. BAR files) to be used as part of an end-to-end CP4I demonstration.

* **jgr-cp4i-mqapi-prem** is an Integration that exposes an MQ Queue as a REST API. The contract can be found [here](https://github.com/gomezrjo/cp4idemo/blob/main/artifacts/jgr-cp4i-mqapi-prem.json). And this is how the flow looks like:

![ACE Integrations Image 0](images/jgr-cp4i-mqapi-prem.png)

* **jgr-cp4i-fwdmq** is an Integration that gets the MQ message produced by the previous flow and forwards it to another queue doing message transformation and protocol conversion to kafka. And this is how the flow looks like:

![ACE Integrations Image 1](images/jgr-cp4i-fwdmq.png)
