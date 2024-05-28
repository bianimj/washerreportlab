<h1>Washer Investigation Report</h1>



<h2>Description</h2>
This report details a forensic investigation of a computer belonging to John Washer, a suspect in several crimes including credit card fraud and check washing.
<br />


<h2>Imaging the Hard Drive</h2>

- <b>Software: FTK Imager</b> 
- <b>Process</b>
    - The suspect's laptop hard drive was imaged after being removed from his home and brought to a lab environment.
    - The system date and time were documented before imaging to assist with file timestamps.
    -  A write blocker was used to ensure the imaging process wouldn't alter any data on the drive.
  -   The image captured a bit-by-bit copy of all information on the drive.
   - Figures 1.0-1.4 showcase the imaging process and details.
<br />

- <b>Verification</b>
    - Hash values were generated to create a digital fingerprint of the image, ensuring its integrity.
    - Figure 1.5 shows the verification of the hash values.



<h2>Active File Review</h2>

- <b>Software: Axiom </b> 
- <b>Process</b>
    - The disk image was loaded into Axiom for forensic analysis.
    - Figures 1.7-1.8 depict the case loading process.
  
- <b>Web Activity</b>
     -  Internet browser history was reviewed, including:
          - Chrome Searches (Figures 1.9-2.5)
          - Internet Explorer Typed URLs (Figures 2.6-2.7)
          - Internet Explorer Cache Records (Figures 2.8-2.9)
    - Analysis revealed potentially suspicious searches related to identity theft and check washing.
  
- <b>Social Media</b>
     -  Social media usage was investigated, with Flickr being the most frequently used platform (Figure 3.0).
 
- <b>Media Analysis</b>
     -  Recovered photos included:
          - Images related to web search history (destroyed hard drives, maps) (Figures 3.1-3.4)
          - A disturbing image of a young girl smoking (Figure 3.5)        
    - Recovered documents included:
         - Incriminating documents like "washers to do list" and "X marks the spot" (Figures 3.7-3.9)
         - Encrypted documents that couldn't be accessed (Figures 4.0-4.4)

- <b>Email Analysis</b>
     -  Emails retrieved from the computer were examined (Figures 4.5-4.6).
 
- <b>Connected Devices</b>
     -  A list of all devices ever connected to the computer was identified (Figure 4.7).
  
<h2>Encryption</h2>
   -  The report notes the presence of encryption software that prevented access to some files (five encrypted files were identified).

<h2>Conclusion</h2>

   - The investigation revealed evidence potentially linking John Washer to the suspected crimes.
   - Web history, documents, and email exchanges suggested involvement in credit card fraud, identity theft, and check washing.
  - The use of unencrypted text documents facilitated the identification of potential plans and codewords used by the suspects.
 - The presence of multiple user profiles on the computer indicates the possibility of other individuals involved.



<h2>Digtal Forensics Walkthrough</h2>

<p align="center">
Figure 1.0: Case Information for Hard Drive Image <br/>
<img src="![Screenshot 2024-05-28 134552](https://github.com/bianimj/washerreportlab/assets/170975732/fd2e1c31-fb91-4dbb-bcb0-555b7d8c93a2)" height="80%" width="80%" alt="Washer Report Steps"/>
<br />
<br />
Figure 1.2: Destination Path for Hard Drive Image  <br/>
<img src="![Screenshot 2024-05-28 134641](https://github.com/bianimj/washerreportlab/assets/170975732/09ea98fc-30e0-4b3c-9e5e-1c72dcf2d9ee)" height="80%" width="80%" alt="Washer Report Steps"/>
<br />
<br />
Figures 1.3-1.4: Hard Drive Imaging Progress <br/>
<img src="![Screenshot 2024-05-28 135206](https://github.com/bianimj/washerreportlab/assets/170975732/4d414c01-559b-416f-9fa4-f3834e54dda4)" height="80%" width="80%" alt="Washer Report Steps"/>
<br />
<br />
Figure 1.5: Hash Value Verification for Hard Drive Image <br/>
<img src="![Screenshot 2024-05-28 135310 (https://github.com/bianimj/washerreportlab/assets/170975732/b2e1d2ff-f08d-4ab4-9f86-814abf3142ea)" height="80%" width="80%" alt="Washer Report Steps"/>
<br />
<br />
Figures 1.7-1.8: Loading Washer's Disk Image into Axiom  <br/>
<img src="![Screenshot 2024-05-28 141140](https://github.com/bianimj/washerreportlab/assets/170975732/ebb95054-5af9-4f87-8142-e896736fac3e)" height="80%" width="80%" alt="Washer Report Steps"/>
<br />
<br />
Figures 1.9-2.5: Suspicious Chrome Searches  <br/>
<img src="![Screenshot 2024-05-28 141528](https://github.com/bianimj/washerreportlab/assets/170975732/bbe42bf5-04b9-499e-ab02-050e43eea75e)
" height="80%" width="80%" alt="Washer Report Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
