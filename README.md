# # AVI

The ControlScript_LetsEncrypt_EVH is a python script that can be added to the NSX ALB (AVI) Controller to request a Let's Encrypt certificate based on 
Enhanced Virtual Hosting (EVH) child Virtual Service. Currently the EVH needs to be named VS-PARENT. You can find more details on my blog 
https://blog.vconsultants.be/how-to-request-lets-encrypt-certificates-on-the-nsx-advanced-load-balancer-based-on-evh/

Credits for the file goes to https://github.com/avinetworks/devops/blob/master/cert_mgmt/letsencrypt_mgmt_profile.py. I only adapted the file to work 
with the setup that I needed, which is based on an EVH parent and child VS.
