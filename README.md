# AttackingAD

Attacking Active Directory --- A Hacking Series
  
This repo will contain slides and information from the Attacking Active Directory Hacking Series talks presented at SecKC.

Module Breakdown:

Part 1: High-level Overview and Flow https://www.youtube.com/watch?v=iWDyzwcSZSs    
Part 2: Infrastructure and Initial Footholds https://www.youtube.com/watch?v=aik8FXm2yE8  
Part 3: Internal Recon, Identifying Attack Paths https://www.youtube.com/watch?v=MTWL7XDH1Ho   
Part 4: Taking the Domain https://www.youtube.com/watch?v=qgLBbtE61-Y  
Part 5: Post-Ex? Automation? Exfiltration? Avoiding Detection? Persistence?<br>
.

Part 1: High-level Overview and Flow - December '17<br>
  Covers the basic theory on attacking Active Directory. It doesnt take a 0-day or uber l33t hacking skills to gain a foothold in an organization. After gaining network access attackers can quickly identify paths to Domain Admin and take over a network. Throughout the series we will walk through all these steps, in detail, to provide a better understanding of what attackers might look like in your network.
  We will continue to follow the path of Gain Credentials, Identify Access, Move Laterally, Gain More Credentials, and repeat until we own ourselves a nice pair of highly priviledged domain credentials.
  
<br>
Part 2: Infrastructure and Initial Footholds ~ January '18<br>
  This talk covers the setup required and used by attackers to manage a campaign. We first get Kali Linux up and running in an AWS environment then move on to our Command and Control software. After we are ready to catch shells, we look at a few different ways to gain an initial foothold into a target network. Using automated tools to scrape the web for possible usernames and email addresses we identify users found in public data breach's and look at how easy it is to guess a password.
  
<br>
<br>
Part 3: Internal Recon, Identifying Attack Paths ~ February '18<br>
  This talk starts out assuming we have our foothold. We take a look at host enumeration to discover networks, software, AV, and other useful information that can be gathered with just one host. Then we move on to network enumeration. We'll take a look at finding high priority targets and where our current creds get us. Next we take a look at tools that automate the recon process like Bloodhound that give us all the routes to DA!
  
<br>
<br>
Part 4: Lateral Movement and Pwning the Domain ~ March '18<br>
  This is it, we've got credentials, we have a path to DA. Now how do we get there?!? We start out with various lateral movement techniques used in traversing the internal networks. We'll move on to different ways of *getting all the creds*. And we will talk about what it means to Pwn the domain, how passwords arent the only thing we are after, and finish with a few things you can do to prevent the easy routes to Domain Admin.
  
<br>


Moar to come!

*I want to make it clear that these are not the only methods used in attacking an infrastructure or that this is a full pentest. This is more or less focused on gaining full control in an Active Directory environment without using exploits in the traditional sense

  
