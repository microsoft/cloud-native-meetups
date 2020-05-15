# Cloud-native and Kubernetes meetup content

This project is an index of cloud-native and Kubernetes meetup content.

## Presentations

| Asset | Description |
|---|-----|
| ![What is cloud native?](what-is-cloud-native.png) <br/> [Cloud-native applications on Azure](presentations/cloud-native-apps-azure.pptx) | Start with presenting the cloud-native applications deck, which describes what they are and goes into a few scenarios like application modernization, real-time telemetry and geo-distributed apps with real customer examples and architecture diagrams. |
|  ![Kubernetes on Azure](k8s-on-azure.png)  <br/> [Kubernetes on Azure](presentations/k8s-on-azure.pptx) | Follow by diving into more details on running Kubernetes on Azure with Azure Kubernetes Service. |
|  ![Azure Cosmos DB](cosmos-db.png) <br/> [Azure Cosmos DB](presentations/azure-cosmos-db.pptx) | Then talk about using Azure Cosmos DB, a globally distributed, massively scalable, multi-modal database service to build modern applications. |


## Demo videos and related 

| Asset | Category | Description | Type | Notes |
|--|-|---|---|---|
| [Kubernetes on Azure Pitch Deck](videos/LearningZoneKubernetesonAzure.wmv) | Overview | Video recording of the Kubernetes on Azure pitch deck. Highlights key Kubernetes use cases and capabilities. | Video | ~10.5 mins |
| [Kurbernetes DevOps](videos/KurbernetesDevOps.wmv) | Cloud native tools | Presentation showcasing end to end devOps with Kubernetes | Video | ~1 min 20 secs |
| [KubeCon DevSpaces Lab Steps](videos/KubeConDevSpacesLabSteps.docx) | Cloud native tools | 10-minute step by step quick start document to increase pull request confidence using Dev Spaces | Document | 3 pages |
| [Azure Dev Spaces](videos/AzureDevSpaces.mp4) | Cloud native tools | Recorded debugging session of Rock, paper, scissors game built using microservices and running on Kubernetes. Debugging done using Azure Dev Spaces extension for Visual Studio Code. Includes discussion of using GitHubs Actions workflow for propagating the fix to rest of the team. | Video | ~6 minutes |
| [Helm 3 Demo Loop](videos/helm3demoloop.mp4) | Cloud native tools | Presentation video overview of key Helm 3 changes and demo of its capabilities | Video | ~7 mins |
| [Helm 3 Demo](videos/helm3demo.mp4) | Cloud native tools | Helm 3 demo showing WordPress site deployment, namespace creation, & site test. | Video | ~3.5 mins |
| [Confidential computing for Kubernetes](videos/confidentialcomputingforKubernetes.mp4) | Security | Overview of Confidential computing and key scenarios.  | Video | ~1 min 20 sec |
| [AZURE Policy overview](videos/Azurepolicyvideo.wmv) | Security | Animated overview video of Azure Policy | Video | ~1 min 10 secs |
|[AKS Diagnostics](videos/AKSDiagnositcs.mp4)|Day 2 operations | Overview of using AKS diagnostics within the Azure portal.|video|23 sec| 
|[Azure Arc Overview](videos/AzureArcKubernetesScreens.pptx) | Day 2 operations |Guided screen by screen overview of Azure Arc for Kubernetes. Covers onboarding, configuration, Policy, and Monitoring.| PowerPoint | 32 slides |
| [Container Insights demo](videos/ContainerInsightsdemo.mp4) | Day 2 operations | Demo of using Azure Monitor for container insights. Shows drilldowns, filtering and similar capabilities to zero in on relevant insights.   | Video | ~8 mins |
| [Deploying to AKS using GitHub Actions](videos/DeployingtoAKSbyusingGitHubActions.docx) | Day 2 operations | 10 minute step by step getting started guide for GitHub Actions for Kubernetes on Azure | Document | 5 pages |
| [Distributed stateful application at scale](videos/DistributedstatefulapplicationatscaleCosmosDB.mp4) | Solutions | AKS and Cosmos DB demo showcasing scale, security and observability. Suitable for technical audience. | Video | ~15 mins |
| [Azure Arc Data Services](videos/AzureArcDataServices.mp4) | Day 2 operations | Demo showing deployment of an Azure SQL DB Managed Instance on a Kubernetes cluster with Azure Arc. | Video | ~3.5 mins |
| [Deploying Apps to AKS by using GitHub Actions](videos/DeployingAppstoAKSbyusingGitHubActions.mov) |Day 2 operations | Demo showing how to deploy Node.js App to Azure Kubernetes Service cluster by using GitHub actions. | Video | ~4 mins |
| [Kubernetes security station Slides](videos/Kubernetessecuritystationdemorecordings.pptx) | Day 2 operations | Title slides for K8s demos stations | PowerPoint | 7 slides |
| [ML Models in Containers](videos\MLModelsinContainers.mp4) | Solutions | Demo showing how to incorporate Azure Machine Learning into business applications built on Azure Kubernetes Service (AKS) and Azure Container Instances (ACI) | Video | ~5.5 mins |
| [KEDA Demo](videos/KEDA.mp4) | Solutions | Demo of Azure Functions in Kubernetes with KEDA. | Video | ~3 mins |



## Takeaway materials

| Cloud Native Tools | Security | Day 2 Operations | Solutions AI/ML | Kubernetes Learning |
|----|-----|----|----|-----| 
| [Best practices](https://aka.ms/aks/bestpractices) | [Solution booklet](https://azure.microsoft.com/en-us/resources/kubernetes-on-azure-solution-booklet/) | [Solution booklet](https://azure.microsoft.com/en-us/resources/kubernetes-on-azure-solution-booklet/) | [Solution booklet](https://azure.microsoft.com/en-us/resources/kubernetes-on-azure-solution-booklet/) | [Learning path](https://azure.microsoft.com/en-us/resources/kubernetes-learning-and-training/) |
| [Azure free credit](https://azure.microsoft.com/en-us/free/) | [Brendan’s DevSecOps webinar](https://info.microsoft.com/ww-ondemand-help-deliver-applications-securely-with-devsecops-us.html) | [Kubernetes Up and running (eBook)](https://azure.microsoft.com/en-us/resources/kubernetes-up-and-running/) |  | [Azure free credit](https://azure.microsoft.com/en-us/free/)|
||[Security essentials whitepaper](https://clouddamcdnprodep.azureedge.net/gdc/gdc8LXmoZ/original)||| [Effectively manage your Kubernetes clusters with built-in best practices (webinar)](https://info.microsoft.com/ww-landing-manage-your-kubernetes-clusters-with-built-in-best-practices.html?LCID=EN-US)|
|||||[Apply Kubernetes best practices for cluster management (webinar)](https://info.microsoft.com/ww-ondemand-apply-kubernetes-best-practices-for-cluster-management.html?lcid=en-us)|
|||||[Best practices to secure your Kubernetes cluster (webinar)](https://info.microsoft.com/ww-ondemand-best-practices-to-secure-your-kubernetes-cluster.html?lcid=en-us)|



## Hands-on content and demos

From content on Microsoft Learn, tutorials to sample applications, use this content to run a 2-3 hour workshop, or extend it over 2 days.

### Getting started with cloud-native application development

- [Get started with Kubernetes on Azure workshop on Microsoft Learn](https://aka.ms/learn/aksworkshop)
- [Rock, paper, scissors, lizard, spock sample application](https://docs.microsoft.com/en-us/samples/microsoft/rockpaperscissorslizardspock/azure-rock-paper-scissors/)

### Azure Kubernetes Service 10 minute labs
- [Deploy using GitHub Actions into Azure Kubernetes Service](https://azure.github.io/kube-labs/1-github-actions.html)
- [Improve debugging experience using Dev Spaces Connect](https://azure.github.io/kube-labs/2-devspaces-connect.html)
- [Build a Dapr pub-sub-app using Visual Studio Code](https://azure.github.io/kube-labs/3-dapr-pubsub.html)
- [Trace applications using Application Insights](https://azure.github.io/kube-labs/5-aks-appinsights.html)

### Bike Sharing application: Streamlining the development workflow

- [Deploy the Bike Sharing application to Azure Kubernetes Service tutorial](https://github.com/Azure/dev-spaces/tree/master/samples/BikeSharingApp)
- [Connect your development machine to an Azure Kubernetes Service cluster tutorial](https://docs.microsoft.com/en-us/azure/dev-spaces/how-to/connect)
- [Team development on Kubernetes using Dev Spaces tutorial](https://docs.microsoft.com/en-us/azure/dev-spaces/quickstart-team-development)
- [Combine GitHub Actions with Dev Spaces in a pull request review tutorial](https://docs.microsoft.com/en-us/azure/dev-spaces/how-to/github-actions)

### Tailwind Traders: A fictitious retail company showcasing the future of intelligent application experiences

- [Tailwind Traders sample application](https://microsoft.github.io/TailwindTraders/)

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

# Legal Notices

Microsoft and any contributors grant you a license to the Microsoft documentation and other content
in this repository under the [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/legalcode),
see the [LICENSE](LICENSE) file, and grant you a license to any code in the repository under the [MIT License](https://opensource.org/licenses/MIT), see the
[LICENSE-CODE](LICENSE-CODE) file.

Microsoft, Windows, Microsoft Azure and/or other Microsoft products and services referenced in the documentation
may be either trademarks or registered trademarks of Microsoft in the United States and/or other countries.
The licenses for this project do not grant you rights to use any Microsoft names, logos, or trademarks.
Microsoft's general trademark guidelines can be found at http://go.microsoft.com/fwlink/?LinkID=254653.

Privacy information can be found at https://privacy.microsoft.com/en-us/

Microsoft and any contributors reserve all other rights, whether under their respective copyrights, patents,
or trademarks, whether by implication, estoppel or otherwise.
