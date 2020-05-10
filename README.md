# Creating-a-Group-Policy-using-Microsoft-PowerShell-to-Configure-the-Authoritative-Time-Server
Creating a Group Policy using Microsoft PowerShell to Configure the Authoritative Time Server

In my 10 Things in AD… presentations, I talk about the importance of having the domain controller that holds the Primary Domain Controller Emulator (PDCe) role configured as the authoritative time source for the forest.  In the PDF that accompanies the presentations, I include a link to a Microsoft Ask the Directory Service Team blog article.  The main problem with that article is there is not enough detail for a lot of people.  Now that Server 2008 and later include PowerShell cmdlets for Group Policy, I thought I would add some detail on creating the Group Policy with PowerShell.
