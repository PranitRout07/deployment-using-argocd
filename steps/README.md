1. Config file to create cluster using kind

<img width="673" alt="kind-config" src="https://github.com/PranitRout07/deployment-using-argocd/assets/102309095/88a4c0a5-52ef-495f-aa99-8a522820caab">


2. Deployment file
<img width="899" alt="deployment-file" src="https://github.com/PranitRout07/deployment-using-argocd/assets/102309095/cd02bfdb-e576-4760-8d11-1cb7783791c5">

   
3. Service file
<img width="790" alt="service-file" src="https://github.com/PranitRout07/deployment-using-argocd/assets/102309095/0154fd22-f842-41fc-acaa-8ce0ffeb47bb">

  
4. Create cluster
<img width="653" alt="created-cluster" src="https://github.com/PranitRout07/deployment-using-argocd/assets/102309095/46293575-e0d4-490a-aae4-5847484841b3">

   
5. Created ArgoCD namespace
<img width="618" alt="created-argocd-namespace" src="https://github.com/PranitRout07/deployment-using-argocd/assets/102309095/5ad36839-74e1-4bf3-93d1-e5f79eb915d8">

6. Apply ArgoCD on K8s Cluster

    <img width="1014" alt="applied argocd on k8" src="https://github.com/PranitRout07/deployment-using-argocd/assets/102309095/d3b2d67d-fea0-4708-a7aa-336e251b7f58">

7. Get the ArgoCD server password
<img width="958" alt="argocd pass" src="https://github.com/PranitRout07/deployment-using-argocd/assets/102309095/98e050b2-2ef0-4efe-8bce-dca7830f9a31">

    
8. PortForward The SVC
<img width="839" alt="port-forwarding the svc" src="https://github.com/PranitRout07/deployment-using-argocd/assets/102309095/dd0761a4-3815-44fd-b042-7b5cc67ab046">

    
9. Login To ArgoCD server
<img width="1272" alt="succeful login to argo server" src="https://github.com/PranitRout07/deployment-using-argocd/assets/102309095/91d02506-0a89-46b9-aa7e-51c822a409c1">

    
10. Now Update ArgoCD server password
<img width="1093" alt="updated password" src="https://github.com/PranitRout07/deployment-using-argocd/assets/102309095/75c5a38c-3268-4d21-9bb3-dad512b66476">

    
11. Connect To Repo Having Manifest Files
<img width="1280" alt="connect to manifest repo" src="https://github.com/PranitRout07/deployment-using-argocd/assets/102309095/1336c573-0d82-482d-88e1-b05731a40397">

    
12. Create An Application From The Connected Repo
<img width="1278" alt="after application is created" src="https://github.com/PranitRout07/deployment-using-argocd/assets/102309095/dc43817c-03cd-4558-abd1-599170714c47">

    
13. Now Access The Website Version 1 In http://localhost:80

    <img width="1279" alt="accessed v1" src="https://github.com/PranitRout07/deployment-using-argocd/assets/102309095/254c145a-d4b7-4299-bfb4-e36d99162560">

14. Now Created Another Branch Feature And Here Updated The Weather-Frontend Image Version

    <img width="1280" alt="updated version in feature branch" src="https://github.com/PranitRout07/deployment-using-argocd/assets/102309095/581ef76d-4ef1-41cf-8c11-709378001f7a">

15. Feature Branch Is 1 Commit Ahead Of Main Branch
<img width="1280" alt="create pull request" src="https://github.com/PranitRout07/deployment-using-argocd/assets/102309095/f1e12383-930b-467d-86ec-f35c34319184">

    
16. Created A Pull Request
<img width="1277" alt="pull request" src="https://github.com/PranitRout07/deployment-using-argocd/assets/102309095/31820142-b8c6-47c3-97eb-511a6bf589ad">

    
17. Merge The Pull Request Into Main Branch
<img width="1280" alt="merge with main" src="https://github.com/PranitRout07/deployment-using-argocd/assets/102309095/5aa7de42-6490-4f63-91d7-afd2ec92a68a">

    
18. After Merge , Now Refresh The ArgoCD Server

    <img width="1280" alt="after refresh you will see suceeded few sec ago" src="https://github.com/PranitRout07/deployment-using-argocd/assets/102309095/c9e52ef9-45e6-4ca4-8f29-202ba83efd3f">

19. Refresh the http://localhost:80 page to get the New Version Website

<img width="1280" alt="new changes has been added" src="https://github.com/PranitRout07/deployment-using-argocd/assets/102309095/15116d69-dda2-4e0a-a047-34b1c0ef08a1">
