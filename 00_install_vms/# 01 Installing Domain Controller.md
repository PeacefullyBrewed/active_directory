# 01 Installing Domain Controller

1. Use 'sconfig' to
    - Change the hostname
    - Change IP to static
    - Change DNS server to self

2. Install windows feature

'''shell
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
'''

