<h1>Simple - Finding Files with Linux</h1>

<h2>Description</h2>
Everyone has to start somewhere, simple. This project consists of a some commands to be used in Linux to simply, find files within Linux.<br>- Google Cybersecurity Certification<br/> 

<br/>

<h2>Project</h2>

<p align="left">
  <b>1. </b>We need to get the current directory information, this is crucial for us to know so we can navigate  to other files <br/>
  <br/>
<img src="https://i.imgur.com/nDczWZB.png" height="80%" width="80%" alt="pwd"/>
<br/>
<br/>
<br/>
<b>2. </b>Now, display names of the files and directories that are in the current directory <br/>
  <br/>
    <img src="https://i.imgur.com/p6opFJX.png" height="80%" width="80%" alt="Current Directory"/>
<br/>
<br/>
<br/>
<b>3. </b>Let's say, our boss wants to know who is in the reports directory, moreso wants to see if they have added Noshiro, the new hire in Finance <br/>
  From here, let's direct ourselves to the 'reports' directory and get a 'list' of who is in there <br/>
  <br/>
    <img src="https://i.imgur.com/eHyqNNX.png" height="80%" width="80%" alt="Finding Noshiro"/><br/>
     <p>Note:<br/>The cd command accepts absolute and relative paths. An absolute path includes all the directories from the root of the file system and starts with a '/' <br/><i>example: cd /home/analyst/reports.</i><br/>
       An alternative is a relative path, which is expressed starting from the current directory and starts without the initial '/'. The above command uses a relative path.<br/><i>example: 'cd reports'.</i><br/>
  <br/> 
  <br/>
<b>4. </b>From here, we can see that under the 'reports' directory, is also another directory called 'users'. Let's navigate to 'users' so we can check what is in there.<br/>
 <br/>
    <img src="https://i.imgur.com/ELYKvGc.png" height="80%" width="80%" alt="Finding Noshiro"/><br/>
<br/>
<br/>
<b>5. </b>We now see  some .txt files! What we can run here, is the 'cat' short for 'concatenate'. This command prints the contents of a file to the shell. You can also specify the file to display using 'absolute' or 'relative' paths that was noted above. For this instance, we demonstrated using an 'absolute' path.<br/>
 <br/>
    <img src="https://i.imgur.com/LH6UhXv.png" height="80%" width="80%" alt="Finding Noshiro"/><br/>
<br/>
<br/>
  <b>6. </b>Finally we have found Noshiro. We can see that Noshiro is already assigned an Employee ID: 1188, and they are already assigned to the Finance department!<br/>
<br/>
<br/>
These steps can be used to fine files, navigate, and explore contents within those files using the 'ls' and the 'cat' commands!<br/>
<br/>
<br/>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
