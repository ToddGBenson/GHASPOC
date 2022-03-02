# GitHub Advanced Security

## Branch Protections
1) Select ‘Settings’

![](Aspose.Words.82e4a104-020e-43b6-b71e-830464967419.001.png)

1) Click on ‘Branches’

![](Aspose.Words.82e4a104-020e-43b6-b71e-830464967419.002.png)

1) Click ‘Add Rule’

![](Aspose.Words.82e4a104-020e-43b6-b71e-830464967419.003.png)

1) Add Branch Name, click on “Require a pull request...” “Require checks” “Include administrators”

![](Aspose.Words.82e4a104-020e-43b6-b71e-830464967419.004.png)
## SAST (Static Analysis Testing)
1) Go to Security and enable "set up code scanning"

![image](https://user-images.githubusercontent.com/8188211/156365015-14cd8266-2f0b-4dff-bca0-4332d1b8a856.png)

2) Click on "Configure CodeQL alerts" to create a codeql scanning file

![image](https://user-images.githubusercontent.com/8188211/156365310-276f31b9-71ee-4e6b-a071-7d44b4a86c54.png)

3) This will create a template file named codeql-analysis.yml under .github/workflows folder. Here we need to configure the scan as per our requirement.

![image](https://user-images.githubusercontent.com/8188211/156365694-a77d0d69-9aad-409f-955c-7e0eb21402b2.png)

4) First set the name of the workflow and the trigger for it. Here, we can configure the trigger based on any event such as a Pull Request or Push to a specific branch. Also, we can also make the workflow run on a certain schedule.

![image](https://user-images.githubusercontent.com/8188211/156366227-b23650a1-8dc0-4649-999c-289012771860.png)

5) Next select the job and specify the runner in which the job should run. (This can be a github runner or a local runner)

![image](https://user-images.githubusercontent.com/8188211/156366540-bc9c8e16-51ca-453d-ac33-dab883880d0b.png)

6) Then intitialize codeql and build the application using autobuild.

![image](https://user-images.githubusercontent.com/8188211/156366876-128527a2-d06c-4a89-9a77-3da610ff03dc.png)

7) Finally perform the scan for the repository and commmit the file to the repository.

![image](https://user-images.githubusercontent.com/8188211/156367137-751eca40-3def-4aaa-abce-701040ef41fb.png)

8) Based on the triggers that we set earlier you could see the workflow getting executed under github actions

![image](https://user-images.githubusercontent.com/8188211/156367478-f7c97821-1411-482f-87de-a483188a82f7.png)

## Secrets
1) Select ‘Settings’

![](Aspose.Words.82e4a104-020e-43b6-b71e-830464967419.001.png)

1) Click ‘Enable’ for Secret scanning

![](Aspose.Words.82e4a104-020e-43b6-b71e-830464967419.005.png)

## SCA (Software Composition Analysis)
1) Select ‘Security’

![](Aspose.Words.82e4a104-020e-43b6-b71e-830464967419.001.png)

1) Click on ‘Enable Dependabot alerts’

![](Aspose.Words.82e4a104-020e-43b6-b71e-830464967419.006.png)

1) Click ‘Enable’ for Dependabot alerts and Dependabot security updates

![](Aspose.Words.82e4a104-020e-43b6-b71e-830464967419.005.png)
##
## DAST (Dynamic Analysis Testing)
Sriram
## Terraform
1) Select ‘Marketplace’

![](Aspose.Words.82e4a104-020e-43b6-b71e-830464967419.007.png)

1) Search for ‘Checkov’

![](Aspose.Words.82e4a104-020e-43b6-b71e-830464967419.008.png)

1) Select ‘Checkov GitHub Action’

![](Aspose.Words.82e4a104-020e-43b6-b71e-830464967419.009.png)

1) Click ‘Use Latest Version’

![](Aspose.Words.82e4a104-020e-43b6-b71e-830464967419.010.png)

1) Click ‘Save to clipboard’

![](Aspose.Words.82e4a104-020e-43b6-b71e-830464967419.011.png)

1) Create a new file in the repo

![](Aspose.Words.82e4a104-020e-43b6-b71e-830464967419.012.png)

1) Name file ‘checkov.yml’ and paste code

![](Aspose.Words.82e4a104-020e-43b6-b71e-830464967419.013.png)

1) Click on ‘Propose new file’

![](Aspose.Words.82e4a104-020e-43b6-b71e-830464967419.014.png)

1) Click on ‘Create pull request’

![](Aspose.Words.82e4a104-020e-43b6-b71e-830464967419.015.png)

1) Have pull request approved
## Container
1. Select the “workflows” folder

![](Aspose.Words.82e4a104-020e-43b6-b71e-830464967419.016.png)

1. Add a file and name it “container.yaml”

` `![](Aspose.Words.82e4a104-020e-43b6-b71e-830464967419.017.png)

1. Run docker file against the container using the following commands 
   1. “Scandemo” – container name

![](Aspose.Words.82e4a104-020e-43b6-b71e-830464967419.018.png)
