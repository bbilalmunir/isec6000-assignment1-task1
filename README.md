# isec6000-assignment1-task1
<h1>1a</h1>
<p>
After successfully creating an account, I logged into the Google Cloud Console.
I created a new project by filling in the project details.
After successfully creating a project and naming it ‘Assignment 1’ on Google Cloud Console, I got redirected to the project dashboard where I opened the terminal.
</p>


<h1>1(b)</h1>
<p>
To create a Kubernetes cluster, I have selected project ‘Assignment 1’.
By clicking on the left-hand menu, I selected ‘Kubernetes Engine’ option and it creates a new standard cluster.
</p>


<h1>1(c) & 1(d)</h1>
<p>
To configure cluster settings, add cluster name, location, and node pool configuration.
Initially it asks for selecting a cluster management tool like Google GKE. I also took care of provisioning the cluster nodes according to the tool I choose.
After doing all the configuration settings, I can easily deploy applications on the cluster by utilizing kubectl or any other deployment tool.
The important step that can have a significant impact on our application’s compatibility and security features is choosing the right Kubernetes version.
By reviewing the release notes of all given Kubernetes version, we can see the insights into the latest features, fixes, and security updates that comes with every release.
</p>


<h1>1(e)</h1>
<p>
I clicked on ‘Create’ to provision my GKE cluster.
Once the cluster is created, it will get connected to the Kubernetes engine.
</p>

<h1>2(a)</h1>
<p>
After creating GKE cluster, I configured kubectl with the cluster by authenticating it with credentials using the following command in the terminal.</p>

```shell
gcloud container clusters get-credentials autopilot-cluster-1 \ --location us-central1
```


<h1>2(b) & 2(c)</h1>
<p>
In the Google Cloud Console, I navigate to the ‘Kubernetes Engine’ > ‘Clusters’ section and click the ‘Connect’ button next to the cluster I made.
To authenticate kubectl with my GKE cluster, I used Google Cloud SDK ‘gcloud’.
To initialize gcloud and authenticate with my Google cloud account, I set my specific project and zone by using following command.</p>
```shell
gcloud container clusters get-credentials autopilot-cluster-1 --region us-central1 --project assignment-1-397507
```




<h1>3 (all parts)</h1>
<p>
To setup a GitHub repository to store my project files, I logged in to my GitHub account.
I clicked on the ‘+’ icon located in the top-right hand side of the GitHub, a drop down opens, I selected ‘New Repository’ from it. Then I give name to the repository which is ‘isec6000-assignment1-task1’ and selected the repository visibility to ‘Public’. While clicking ‘Create repository’</p>
  
I initialize it with README file. ‘ADD LINK HERE’
