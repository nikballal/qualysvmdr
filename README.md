# Qualys VMDR
Vulnerability Assessment using Qualys Cloud


- Current status of the asset is as shown below with a TruRisk Score of 82 (Low) with a criticality score of 3 with 5 being the the highest score an asset can be alloted as very critical.

![asset criticality edited](https://user-images.githubusercontent.com/89782464/226181011-30f33217-128e-4349-8894-f6bbc637c7dc.jpg)



- Upon installation of the VMDR Cloud Agent provided by Qualys Cloud, it is observed under the VMDR - vulnerabilities tab, the total vulnerabilities detected to be 26.


<img width="954" alt="total vulnerabilities" src="https://user-images.githubusercontent.com/89782464/226181056-90f46335-5e37-4a61-b1be-1739481e2236.PNG">

- Out of the 26, we query out for the patchable vulnerabilities as per the queries below for the local Windows machine asset.
<img width="962" alt="patchable vulnerabilities" src="https://user-images.githubusercontent.com/89782464/226181115-8578c941-cd2b-4dd2-9a25-3d627a87cebf.PNG">

- Under Patch Management of the Qualys Cloud Platform, the available patches are as shown
<img width="959" alt="windows host - patches" src="https://user-images.githubusercontent.com/89782464/226181173-0fa84bdb-4e10-4890-950e-5e14ca1c40c9.PNG">

- A job to patch the vulnerabilities is created, under Patch Mangement of the Qualys Cloud Platform. 

<img width="892" alt="deploy patches - Mar 31 - 12am - 6hr" src="https://user-images.githubusercontent.com/89782464/226181397-beace2f3-c265-403d-8987-d3b8c891345e.PNG">

- A scheduled patch is setup to take place on 31st of Mar at 12am in a 6hr window as shown below

<img width="696" alt="confirmation" src="https://user-images.githubusercontent.com/89782464/226181455-ceaf68ae-4769-4e51-9b70-52a99232ed00.PNG">

- Final Status

<img width="955" alt="final status" src="https://user-images.githubusercontent.com/89782464/226181488-743810f9-3749-4af8-8c75-583d06e52c08.PNG">
