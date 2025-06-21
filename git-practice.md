SSH Authentication
1. import the public key in github server
2. create a file called config in .ssh folder inside user directory

follow the below syntax

# this is for DAWS-74S
Host github.com
  HostName github.com
  User git
  IdentityFile ~/.ssh/sivakumarreddy.pem

#techworldwithsiva
Host github.com-t
  HostName github.com
  User git
  IdentityFile ~/.ssh/techworldwithsiva

  if you have existing folder, how can you push to GitHub:---
  ----------------------------------------------------------------

  1. class -12 is pending above concept 