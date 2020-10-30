# Krustlet on Azure

This template deploys and sets up a customized Krustlet instance on an Ubuntu Virtual Machine. It also deploys a Virtual Network and a Kubernetes cluster (via AKS).

You can set common Krustlet server properties as parameters at deployment time. Once the deployment is successful, you can connect to the Kubernetes cluster using `az aks get-credentials`.

For more information on how to use this template, refer to [Creating a custom web server using an Azure Resource Manager template]().

[![Deploy To Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fbacongobbler%2Fkrustlet-on-azure%2Fmain%2Fazuredeploy.json)
