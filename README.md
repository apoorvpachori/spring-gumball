# spring-gumball ci/cd example

### This example demonstrates the following two GitHub Workflows.

* https://help.github.com/actions/language-and-framework-guides/building-and-testing-java-with-gradle

* https://github.com/google-github-actions/setup-gcloud/tree/master/example-workflows/gke

### Build Dependencies

* Gradle 5.6
* JDK 11

# CI Workflow

Running the Github Actions Workflow on commit:

![Screen Shot 2022-11-28 at 1 18 42 PM](https://user-images.githubusercontent.com/41656573/204399628-103fe6b1-1d37-4cc8-97bd-4a765bd0e76b.png)

![Screen Shot 2022-11-28 at 1 17 18 PM](https://user-images.githubusercontent.com/41656573/204399518-952963fe-0c88-40e6-a5d7-ffde2fea3ca1.png)

Successfully completed

![Screen Shot 2022-11-28 at 1 18 01 PM](https://user-images.githubusercontent.com/41656573/204399598-7e4bea4b-3911-4133-9b6b-d94fa016d4fe.png)

<img width="1440" alt="Screen Shot 2022-11-28 at 2 06 24 PM" src="https://user-images.githubusercontent.com/41656573/204399644-bf1a9285-8b15-45da-80e3-098b2efe04a6.png">

# CD Workflow

Creating service account:

<img width="1440" alt="Screen Shot 2022-11-28 at 2 40 14 PM" src="https://user-images.githubusercontent.com/41656573/204399733-0f0dc131-5374-4724-b825-c38c89199b21.png">

Creating Key for service account:

<img width="1440" alt="Screen Shot 2022-11-28 at 2 40 14 PM" src="https://user-images.githubusercontent.com/41656573/204399790-1cf0711e-f8b7-4302-b35f-75a6f0c27a9a.png">

Setting secrets on Github repo:

<img width="1440" alt="Screen Shot 2022-11-28 at 3 09 30 PM" src="https://user-images.githubusercontent.com/41656573/204399920-709994bc-5f1d-435f-9815-101cc338af72.png">

Setting up release:

<img width="1440" alt="Screen Shot 2022-11-28 at 2 47 35 PM" src="https://user-images.githubusercontent.com/41656573/204399971-5cba5f78-6f45-4574-81b3-4393ff16f331.png">

Github action workflow triggered and running on release:

<img width="1440" alt="Screen Shot 2022-11-28 at 2 47 42 PM" src="https://user-images.githubusercontent.com/41656573/204400008-5bd2925d-a5d9-4c50-bb27-ef95a198b967.png">

<img width="1440" alt="Screen Shot 2022-11-28 at 2 48 57 PM" src="https://user-images.githubusercontent.com/41656573/204400021-04fae033-4430-4df8-bec1-1db1e1f6b5b3.png">

Workflow run successfully:

<img width="1440" alt="Screen Shot 2022-11-28 at 2 49 41 PM" src="https://user-images.githubusercontent.com/41656573/204400053-38a588fb-f2e7-460a-8a0e-824afcca6629.png">

<img width="1440" alt="Screen Shot 2022-11-28 at 2 49 59 PM" src="https://user-images.githubusercontent.com/41656573/204400071-a938f563-792b-46cf-8532-da9ab535a845.png">

GKE Set up:

<img width="1440" alt="Screen Shot 2022-11-28 at 2 50 31 PM" src="https://user-images.githubusercontent.com/41656573/204400620-0b93b59c-f1b4-42aa-8bf2-ddea0a61498e.png">

<img width="1440" alt="Screen Shot 2022-11-28 at 2 50 41 PM" src="https://user-images.githubusercontent.com/41656573/204400652-4c8fddac-3d11-4ac3-a16b-74908410720a.png">

Setting up the ingress:

<img width="1440" alt="Screen Shot 2022-11-28 at 2 53 02 PM" src="https://user-images.githubusercontent.com/41656573/204400693-01448c39-ef6f-4ce1-8f92-9149b2a718b4.png">

<img width="1440" alt="Screen Shot 2022-11-28 at 2 53 14 PM" src="https://user-images.githubusercontent.com/41656573/204400709-5af6d752-ed7b-4d74-a8b7-5231e900c205.png">

Final product:

<img width="1440" alt="Screen Shot 2022-11-28 at 2 57 03 PM" src="https://user-images.githubusercontent.com/41656573/204400758-450a0864-63ef-4fa7-b79b-86e940813db9.png">


