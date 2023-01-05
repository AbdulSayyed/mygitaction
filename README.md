## [Gitversion](https://gitversion.net/docs/)

- It helps generating semantic version numbers based on your git repo history. These version numbers can be used in number of ways in developing softwares. GitVersion uses git graph to generate the tagging and often used with `gitflow` a tool present in git.
- [Semantic versioning](https://semver.org/) is a concept of giving softwares version numbers based on some specification. Gitversion is just one tool that implements this specification.

### How to use Gitversion ?

- Using command line
- A continuous server pipeline
- Microsoft build task with NuGet

### Installing on Windows

- `choco install GitVersion.Portable`

```bash
λ choco install GitVersion.Portable                                                                            
Chocolatey v0.12.1                                                                                             
Installing the following packages:                                                                             
GitVersion.Portable                                                                                            
By installing, you accept licenses for the packages.                                                           
Progress: Downloading GitVersion.Portable 5.11.1... 100%                                                       
                                                                                                               
GitVersion.Portable v5.11.1 [Approved]                                                                         
gitversion.portable package files install completed. Performing other installation steps.                      
The package GitVersion.Portable wants to run 'chocolateyInstall.ps1'.                                          
Note: If you don't run this script, the installation will fail.                                                
Note: To confirm automatically next time, use '-y' or consider:                                                
choco feature enable -n allowGlobalConfirmation                                                                
Do you want to run the script?([Y]es/[A]ll - yes to all/[N]o/[P]rint): y                                       
                                                                                                               
Added C:\ProgramData\chocolatey\bin\gv.exe shim pointed to '..\lib\gitversion.portable\tools\gitversion.exe'.  
Environment Vars (like PATH) have changed. Close/reopen your shell to                                          
 see the changes (or in powershell/cmd.exe just type `refreshenv`).                                            
 ShimGen has successfully created a shim for gitversion.exe                                                    
 The install of gitversion.portable was successful.                                                            
  Software install location not explicitly set, it could be in package or                                      
  default install location of installer.                                                                       
                                                                                                               
Chocolatey installed 1/1 packages.                                                                             
 See the log for details (C:\ProgramData\chocolatey\logs\chocolatey.log).                                      

```

- Once installed use `gitversion /help` or `gitversion /version`. The output of the version is shown below
- 5.11.1+Branch.support-5.x.Sha.82cbf2c587897ed9906624f3b55f200ac99f084e
- Its help can be generated to understand how it helps us in building semantic versioning

