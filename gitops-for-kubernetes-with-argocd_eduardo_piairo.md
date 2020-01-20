GitOps For Kubernetes with ArgoCD

=================================================

* Speaker   : Eduardo Piairo
* Available : first day, second day, third day
* Length    : 30 minutes
* Language  : English

Description
-----------

This talk is about how I added the missing piece on my companies deployment pipeline - the deliver step - using ArgoCD. ArgoCD is delivery tool for Kubernetes that allow a declarative approach by comparing the definition of the resource in the source control repository with the current state of the same resource in the kubernetes cluster. I will describe how ArgoCD allowed to automate a "simple" decision: to deploy or not to deploy. 

Speaker Bio
-----------

Operations engineer @ Skim Technologies that enjoys build software, pipelines and communities. Always ready to learn the path to production using source control, continuous integration and continuous delivery for applications, databases and infrastructure. The deployment pipeline is my favourite technical and cultural tool. 

Links
-----

* Blog: https://www.eduardopiairo.com/
* Company: [Skim Technologies](https://www.skimtechnologies.com/) 
* GitHub: https://github.com/eduardopiairo
* Photo: https://www.eduardopiairo.com/about/

Extra Information
-----------------

When I joined my company there was missing a step in the deployment pipeline: the delivery step. The delivery process was manual meaning that someone (me) would need to create/upgrade the applications on the Kubernetes cluster. The urgent goal was to automate this process and for that we introduced ArgoCD in our pipeline.
ArgoCD allows a declarative approach by comparing the definition of the resource in the source control repository with the definition of the same resource in the kubernetes cluster. In simple words, it compares the definition in the git repository with the current state in the kubernetes cluster and give the diff.
Whit this "simple" capability is possible to integrate in the pipeline (in a automated way) an importante decision: deploy or not to deploy a specific definition in a target environment.


* https://www.youtube.com/watch?v=0YihV2kfb24
* https://www.youtube.com/watch?v=Txjf3nsKxVk&t=8s
