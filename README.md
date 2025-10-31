\# AWS CI/CD Activity - Launch Windows VM



\## Objective

Launch a Windows virtual machine in AWS and connect to it from a local Windows machine.



\## Steps Followed

1\. Logged in to AWS Management Console.

2\. Selected \*\*EC2\*\* → \*\*Launch Instance\*\*.

3\. Chose \*\*Microsoft Windows Server 2022 Base\*\* as the AMI.

4\. Selected instance type \*\*t2.micro\*\* (Free Tier eligible).

5\. Created or selected an existing key pair (`my-keypair.pem`).

6\. Configured security group to allow \*\*RDP (port 3389)\*\*.

7\. Launched the instance.

8\. Copied the \*\*Public IPv4 address\*\* of the instance.

9\. Connected using \*\*Remote Desktop Connection (mstsc)\*\* on my local Windows PC.



\## Verification

\- Successfully logged in using RDP.

\- Instance running in AWS Console.

\- Free Tier usage confirmed.



\## Notes

This repository documents the setup and connection process for CI/CD lab work.



---



\*\*Author:\*\* \[CHSPsreekar](https://github.com/CHSPsreekar)

