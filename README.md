# Sample Allocation and Distribution Tools
These tools helps users implement a sampling design using Google Earth Engine

*New to Google Earth Engine? - Scroll to the bottom for Appendix A - Register with GEE

The Sample Allocation and Distribution Tool repository contains tools for:
 -  Random Sampling
 -  Systematic Sampling
 -  Manual Stratification
 -  Stratified Random/Systematic Sampling

A) Select Random Sampling or Systematic Sampling files in the repository

For both...

- Begin by clicking "Run" at top of page - This loads the "User Interface"
![GEE_Run](https://github.com/user-attachments/assets/a4f6657a-615c-47eb-9a57-1e9f92f4a652)
- You can now choose to "Draw [your] Study Area" manually using the GEE Drawing tools:
  
https://github.com/user-attachments/assets/b6a1aaac-ab95-4561-abd2-ec2fc33cc622

- Or you can upload a shapefile

https://github.com/user-attachments/assets/0f41d6b1-1d3e-4f69-a59f-677e6ce98f6a

- Once loaded, click "Run" again to load the boundary into the code
  
https://github.com/user-attachments/assets/e3081490-9bd5-4215-9d31-313456ea2a51

- Calculate Sample Allocation - From UNFCCC https://cdm.unfccc.int/methodologies/ARmethodologies/tools/ar-am-tool-03-v2.pdf
- Define "accuracy" = Mean +/- %error, 10% is typical, 5% is academic, 10-20% is practical
- Define "precision" = P-value, probaility your study is within your "accuracy" range, 10% is typical, 5% is academic, 10-20% is practical
- Select "Calculate Sample Allocation"

https://github.com/user-attachments/assets/444f541a-3aa3-49cf-840f-efbddf02108f

- Input your sample size in the "Enter Sample Size Box"



https://github.com/user-attachments/assets/6bcb6d6b-17e4-4233-83b2-2bded9f7e316



- Export your sample locations



https://github.com/user-attachments/assets/586d63f6-476f-48e8-bf47-62ba2789450e



Now you go to these locations and collect some data:
Resources
- https://wwf.ca/carbon-measurement/#:~:text=In%20Canada%2C%20327%20billion%20tonnes,the%20atmosphere%2C%20accelerating%20climate%20change.
- https://link.springer.com/article/10.1007/s13157-023-01722-2
  

When you've collected all your data - #Click Here to analyse it


Appendix A - Register with GEE
Steps
  1. To sign up for a Google account, go to https://code.earthengine.google.com and select I want to register a new project.
  2. Create a Google Cloud project - GEE now requires connecting to a Google Cloud project (GCP), available for paid commercial use or free for academic and research purposes.
  3. Select Unpaid usage and choose your project type (e.g. Academia & Research, Government, Non-profit). Select Next.
  4. Create or choose an existing GCP to register your project, then select a Project-id and optionally a Project name. Select Continue to summary. A red alert will appear at the bottom of the page, requesting that you accept the Cloud Terms of Service to continue. Select the link. Select Register a Noncomercial or Commercial Cloud project and follow the instructions to create your account.
  5. You will be redirected to the Google Cloud page, where you will see a welcome form. Read and accept the Terms of Service (1) and optionally (2) check the box for Email updates. Select Agree and continue (3).
