<h1>📕Washer Investigation Report</h1>



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
   - Figures 1.0-1.2 showcase the imaging process and details.
<br />

- <b>Verification</b>
    - Hash values were generated to create a digital fingerprint of the image, ensuring its integrity.
    - Figure 1.3 shows the verification of the hash values.



<h2>Active File Review</h2>

- <b>Software: Axiom </b> 
- <b>Process</b>
    - The disk image was loaded into Axiom for forensic analysis.
  
- <b>Web Activity</b>
     -  Internet browser history was reviewed, including:
          - Chrome Searches (Figure 1.5)
          - Internet Explorer Typed URLs 
          - Internet Explorer Cache Records 
    - Analysis revealed potentially suspicious searches related to identity theft and check washing.
  
- <b>Social Media</b>
     -  Social media usage was investigated, with Flickr being the most frequently used platform.
 
- <b>Media Analysis</b>
     -  Recovered photos included:
          - Images related to web search history (destroyed hard drives, maps) 
          - A disturbing image of a young girl smoking       
    - Recovered documents included:
         - Incriminating documents like "washers to do list" and "X marks the spot" 
         - Encrypted documents that couldn't be accessed 

- <b>Email Analysis</b>
     -  Emails retrieved from the computer were examined.
 
- <b>Connected Devices</b>
     -  A list of all devices ever connected to the computer was identified.
  
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
<img src="https://i.imgur.com/spdEfcY.png" height="80%" width="80%" alt="Washer Report Steps"/>
<br />
<br />
Figure 1.1: Destination Path for Hard Drive Image  <br/>
<img src="https://i.imgur.com/OD7NbIt.png" height="80%" width="80%" alt="Washer Report Steps"/>
<br />
<br />
Figures 1.2: Hard Drive Imaging Progress <br/>
<img src="https://i.imgur.com/YVSUask.png" height="80%" width="80%" alt="Washer Report Steps"/>
<br />
<br />
Figure 1.3: Hash Value Verification for Hard Drive Image <br/>
<img src="https://i.imgur.com/rbqaidC.png" height="80%" width="80%" alt="Washer Report Steps"/>
<br />
<br />
Figures 1.4: Loading Washer's Disk Image into Axiom  <br/>
<img src="https://i.imgur.com/1DK2Ptf.png" height="80%" width="80%" alt="Washer Report Steps"/>
<br />
<br />
Figures 1.5: Suspicious Chrome Searches  <br/>
<img src="https://i.imgur.com/bvqhlXU.png" height="80%" width="80%" alt="Washer Report Steps"/>
<br />
<br />

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
