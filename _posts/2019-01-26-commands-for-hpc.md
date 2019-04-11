---
layout: post
title: "Some useful Commands"
date: 2019-01-26
---
<h1> Slurm commands </h1>
<ul> 
  <li> squeue -j jobID: check job status</li>
  <li> squeue -u username: check a user's all jobs</li>
  <li>  scancel jobID: cancel a job</li>
</ul>

<h1> Linux commands</h1>
<ul>
  <li>remove files without asking: rm -f filename </li>
  <li>du -h foldername: list disk space usage of all the files in the folder</li>
  <li>du -sh foldername: list total disk space usage of the folder</li>
  <li>ls -l foldername: list file permissions in the folder in the following format <br />
    drwxr-xr-x 2 user group       4.0K 2009-08-13 10:16 docs ,<br/>
  where the first letter denotes the file type. - means a regular file; d means a folder; l means symbolic link. <br/>
  The next three letters represent the permissions of the user. The 5th, 6th, and 7th letters repsent the permissions of the group. The last 3 letters represent the permissions of other users. <br/>
  </li>
  </ul>
