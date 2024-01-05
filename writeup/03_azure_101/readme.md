## Objective "Azure 101"

![](azure_1.png)

### Location 

Christmas Island: Rudolph's Rest (walk to the left most part of the island)

Also note the "Penetration Test Report" in the middle of the Island
for some very usefull hints about the later challenges (esp. SSHenanigans)

### Task and Solution

- az help
- az account show
- az group list
- az functionapp list --resource-group northpole-rg1
- az vm list -g northpole-rg1
- az vm list -g northpole-rg2
- az vm run-command invoke -g northpole-rg2 -n NP-VM1 --command-id RunShellScript --scripts "ls"
