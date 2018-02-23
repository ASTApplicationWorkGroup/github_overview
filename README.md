On premise Github does exist https://github.com/pricing/business-enterprise cost is $21 a month per user.  Git is provided as a virtual machine.  You can get a trial for this.

FOR WINDOWS USERS THAT WANT TO USE SSH TO LOG ONTO GITHUB
(https://vladmihalcea.com/tutorials/git/windows-git-ssh-authentication-to-github/)
This explains how to generate (with puttygen) a public/private key pair and install the public key on github and store the private key in the ssh keystore.  

FOR LINUX/MAC USERS THAT WANT TO USE SSH TO LOG INTO GITHUB
Step one create ssh private/public key pair and add it to your .ssh store (this is very similar to Windows)
Step two create add SSH key to your github account https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/ 

SSO TO LOG INTO GITHUB
You can use SSO if configured using SAM with an SSH key https://help.github.com/articles/authorizing-an-ssh-key-for-use-with-a-saml-single-sign-on-organization/
