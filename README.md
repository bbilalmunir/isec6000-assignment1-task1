# isec6000-assignment1-task1
<h1>1(a)</h1>
<p>
After successfully creating an account, I logged into the Google Cloud Console.
I created a new project by filling in the project details.
After successfully creating a project and naming it ‘Assignment 1’ on Google Cloud Console, I got redirected to the project dashboard where I opened the terminal.
</p>
![1a](https://github.com/bbilalmunir/isec6000-assignment1-task1/assets/143603777/1692a240-3edd-45c1-b44c-113aa6d230cd)


<h1>1(b)</h1>
<p>
To create a Kubernetes cluster, I have selected project ‘Assignment 1’.
By clicking on the left-hand menu, I selected ‘Kubernetes Engine’ option and it creates a new standard cluster.
</p>
![1b](https://github.com/bbilalmunir/isec6000-assignment1-task1/assets/143603777/8968d262-a453-4977-ba4d-af42e0d0c5a5)


<h1>1(c) & 1(d)</h1>
<p>
To configure cluster settings, add cluster name, location, and node pool configuration.
Initially it asks for selecting a cluster management tool like Google GKE. I also took care of provisioning the cluster nodes according to the tool I choose.
After doing all the configuration settings, I can easily deploy applications on the cluster by utilizing kubectl or any other deployment tool.
The important step that can have a significant impact on our application’s compatibility and security features is choosing the right Kubernetes version.
By reviewing the release notes of all given Kubernetes version, we can see the insights into the latest features, fixes, and security updates that comes with every release.
</p>
![1c_d](https://github.com/bbilalmunir/isec6000-assignment1-task1/assets/143603777/b22a2b16-fad6-4846-95a6-18e4a6f6c471)


<h1>1(e)</h1>
<p>
I clicked on ‘Create’ to provision my GKE cluster.
Once the cluster is created, it will get connected to the Kubernetes engine.
</p>
![1e](https://github.com/bbilalmunir/isec6000-assignment1-task1/assets/143603777/f66f0ae8-ccca-429b-9f8e-51de6f7b7498)

<h1>2(a)</h1>
<p>
After creating GKE cluster, I configured kubectl with the cluster by authenticating it with credentials using the following command in the terminal.</p>

```shell
gcloud container clusters get-credentials autopilot-cluster-1 \ --location us-central1
```
![2a](https://github.com/bbilalmunir/isec6000-assignment1-task1/assets/143603777/95e9c41e-ac9f-4b25-9e8b-e934ea97e30d)


<h1>2(b) & 2(c)</h1>
<p>
In the Google Cloud Console, I navigate to the ‘Kubernetes Engine’ > ‘Clusters’ section and click the ‘Connect’ button next to the cluster I made.
To authenticate kubectl with my GKE cluster, I used Google Cloud SDK ‘gcloud’.
To initialize gcloud and authenticate with my Google cloud account, I set my specific project and zone by using following command.</p>

```shell
gcloud container clusters get-credentials autopilot-cluster-1 --region us-central1 --project assignment-1-397507
```
![2b](https://github.com/bbilalmunir/isec6000-assignment1-task1/assets/143603777/365ad320-fe3e-4608-9f83-e21f2fe0f752)
![2c](https://github.com/bbilalmunir/isec6000-assignment1-task1/assets/143603777/e84e4dbc-2dbc-48ba-87f8-53cf575fe250)


<h1>3</h1>
<p>
  ![3](https://github.com/bbilalmunir/isec6000-assignment1-task1/assets/143603777/62f691ca-c105-45d9-b2ec-453f579ab6e0)

To setup a GitHub repository to store my project files, I logged in to my GitHub account.
I clicked on the ‘+’ icon located in the top-right hand side of the GitHub, a drop down opens, I selected ‘New Repository’ from it. Then I give name to the repository which is ‘isec6000-assignment1-task1’ and selected the repository visibility to ‘Public’. While clicking ‘Create repository’ I initialize it with README file. <a href="https://github.com/bbilalmunir/isec6000-assignment1-task1">README.md<a>
