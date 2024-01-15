<h1>Vulnerability Scanning - Metasploitable 2 </h1>

<h2>Description</h2>
In the test environment of Metasploit 2, vulnerability scanning is being performed to collect results.  Utilizing the nmap command line tool, scanned for open TCP and UDP ports on MS2, discovered the Root shell port number, and identified the non-standard port along with its version. 
<br />
<h2>Tools and Services Used</h2>

- <b>Metasploitable2</b> 
- <b>Nmap</b>

<h2>Environments Used </h2>

- <b>Virtual Box</b>

<h2>Program walk-through:</h2>
Checking how many TCP ports are open on MS2: <br/>
<br/>

![scanning01](https://github.com/Debosree-090/learning_labs/assets/96138088/1580313a-5c5b-48c2-94e5-c78d540decfd)
<br/>

Checking how many UDP ports are open on MS2: <br/>

![scanning02](https://github.com/Debosree-090/learning_labs/assets/96138088/f762d4d6-e105-4e51-8d28-b05ac9522d15)
<br/>

Metasploitable Root Shell: <br/>

![scanning03](https://github.com/Debosree-090/learning_labs/assets/96138088/e355d638-b4ad-4818-8875-68f54e63a64a)
<br/>

FTP port running on non-standard port:</br>

![Scanning04](https://github.com/Debosree-090/learning_labs/assets/96138088/3e701ecc-d05e-41fd-bc86-5c683dad8720)
<br/>

![Scanning05](https://github.com/Debosree-090/learning_labs/assets/96138088/fa385994-9f4d-402c-93b3-11262876211b)

Version of FTP checking: </br>

![Scanning06](https://github.com/Debosree-090/learning_labs/assets/96138088/03ab130e-2495-480b-9e92-468a45d00f33)





