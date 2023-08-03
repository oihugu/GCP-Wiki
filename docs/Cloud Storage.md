---
type: GCP Component 
share: true
creation date: 2023-08-01 16:39
modification date: Tuesday 1st August 2023 16:39:15
related:
---


- Unstructured Data
- Standard Storage
	- Frequently Accessed Data #Hot_Data
	- Brief Periods of Time
- Nearline Storage
	- Data Accessed or Modify Once per Month
	- Ex: Backups, data archives
- Coldline Storage
	- Data Accessed or Modify Once per 90 days
- Archive Storage
	- Data Accessed or Modify Once a year
	- Has to stay the minimum of 365 days in GCP


<details>
<summary>How can we decide if the project needs Nearline, Coldline or Archive storage in GCP?</summary>
The decision on whether to use Nearline, Coldline, or Archive storage in GCP depends on the frequency of data access and the desired cost-efficiency for the project.

- Nearline Storage: 1 access in 30 days
- Coldline Storage: 1 access in 90 days
- Archive Storage: : 1 access in 365 days
</details>
<!--ID: 1691034592930-->


<details>
<summary>What means the concept of Hot Data?</summary>
Frequently Accessed Data
</details>
<!--ID: 1691034662982-->

