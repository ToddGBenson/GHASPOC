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
1) Go to Security and enable code scanning alerts
![image](https://user-images.githubusercontent.com/8188211/156360110-4ddabc75-5153-4db8-908f-08cfc5a52dc6.png)

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
