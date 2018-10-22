# Sparta_AWS_Instructions

**By : Erica P da Silva Correia**

#### Description :

Write a Readme file with instructions as to how to create and run a machine on AWS.

-----

#### Tech Used :
**AWS**

-----
##### how to download :


1. go to the github page [**https://github.com/EricaDaSilvaCorreia**](https://github.com/EricaDaSilvaCorreia)
2. Click repositories and select the repository [**Sparta_AWS_Instructions**](https://github.com/EricaDaSilvaCorreia/Sparta_AWS_Instructions)
3. Click 'Clone or Download'
4. Choose between **Open in Desktop**, **Download ZIP**, **Clone with SSH**, **Clone with HTTPs**

-----
##### how to make and run an AMI :

1. Log into your AWS account 
2. Once on the Dashboard page, go to your navbar and click on services
3. In the services section select EC2 (under Compute on the to left-hand-side).
4. Once in EC2, click on **Launch Instance** 
5. **Step 1:** Select your desired AMI (Amazon Machine Image) ensuring you choose the free tiers.
6. **Step 2:** Select your desired Instance Type.
7. **Step 3:** Configure Insance Details as Required.(For Paid AMI)
8. **Step 4:** Add Storage and adujst storage specifications as required.(For Paid AMI)
9. **Step 5:** Add tags to your machine (for example Name)
10. **Step 6:** Configure Security Specifications (ssh)
11. Once you're done with these steps click **Review and Launch**
12. Review all your details and make sure everything is correct.
13. Once Reviewed click **Launch** at the bottom right and this will show you a pop-up to select a ssh key.
14. Select the relevant key.
15. Once this is done, your machine will Launch on AWS.
16. Ask your supervisor for the private key.
17. Open a Terminal on your computer.
18. **Your key must not be publicly viewable for SSH to work.** 
19. If Necessary use the following command : chmod 400 PrivateKeyName.pem
20. Connect to your instance using its Public DNS: ssh -i "PrivateKeyName.pem" SelectedAMI@AMIPublicDNS 

-----


##### Challenges :

Overall, there weren't any challenges with this homework. 

-----

##### Take-Aways :

All in all I think today was very interesting. I enjoyed learning about Jenkins and AWS and I'm looking forward to tomorrow!

I give it a 8/10.

-----
