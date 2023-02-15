**Chart Details:**
* Maintainers: Radium Platform (CI/PPB4)
* Helm Chart: Radium-Dummyapp
* Description: We are using this HELM Chart, to deploy dummy application in your project every one hour once to check the cluster availability and  it's related sources.

**Note:** Please do not Modify / Edit / Delete this helm chart without informing to Radium Operations Team <Operations.Radium@de.bosch.com> .

CONTENTS OF THIS FILE:
----------------------
	* This is referrence Radium Platform Test application.

	* It has contains.
		- Namespace
		- Statefulset
		- Service
		- Ingress
		- Secret
	
Source of Document:
-------------------
* how to use radium platform:
	- https://inside-docupedia.bosch.com/confluence/x/rZbBh
* ArgoCD:
	- https://inside-docupedia.bosch.com/confluence/x/C5jBh

Purpose of Dummyapp:
--------------------
	* Every one hour once we are redeploying the application to check the cluster availability
	* Dummy Helm chart reference for all customer
	* To Understand app deployment via ArgoCD
	* how to define clusterID:ProjectID in the namespace annotation
	* How to Define Resource quota in namespace annotation

Firewall testing:
-----------------
netcat (nc) , Curl commands are available on the pod. Using this you can check the communication to required URLs
