Contains a Vagrant file to create:  
- Debian server   
- Fedora server   
- Windows 10 Deskop   

Instructions:   
To create/bring up all three machines:   
```
vagrant up
```
Or individual machine
```
vagrant up Debian
vagrant up Fedora
vagrant up Windows
```
Shutdown and restart with: 
```
vagrant halt
vagrant reload
```
And of course the best part, to destroy everything: 
```
vagrant destroy
```

**Note:   
Just a heads up:**   
Windows creation and provision will take a while!   
Also it might take a while after the creation for WindowsMinion to show up to your Master.   
There is an added wait timer because of that in the provision part, but it might still take a little longer.
