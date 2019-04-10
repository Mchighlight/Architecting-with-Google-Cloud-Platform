# Architecting-with-Google-Cloud-Platform Specialization
Architecting with Google Cloud Platform是Coursera上的課程，此為記錄學習的Repo
課程為期一個月
# Course Outline
* 第一週: 介紹Google cloud platform服務大綱<br />
  [Week1: Google Cloud Platform Fundamentals: Core Infrastructure](https://www.coursera.org/learn/gcp-fundamentals)<br />
* 第二至五週: 深入實做每個服務的功能，每一週都會有不同的Lab，Lab是由Qwiklabs Inc.所提供。<br />
如需要實作module內的lab需要購買學習點數或著是參加Coursera的Architecting-with-Google-Cloud-Platform Specialization。<br />
Lab運作方式:Qwiklabs會提供一組Google的帳號，帳號內已經擁有gcp的使用權。參與者需在時間到點前，按照指定的任務去完成lab。<br />
[Week2: Essential Cloud Infrastructure: Foundation](https://www.coursera.org/learn/gcp-infrastructure-foundation)<br />
[Week3: Essential Cloud Infrastructure: Core Services](https://www.coursera.org/learn/gcp-infrastructure-core-services)<br />
[Week4: Elastic Cloud Infrastructure: Scaling and Automation](https://www.coursera.org/learn/gcp-infrastructure-scaling-automation)<br />
[Week5: Elastic Cloud Infrastructure: Containers and Services](https://www.coursera.org/learn/gcp-infrastructure-containers-services)<br />
* 第六週: 將前五週的內容做統整，並進行腦力激盪如何設計出高穩定、高擴張性的產品，主要的課程內容偏向於開發設計而非專注於實作上。<br />
首先將產品成三大層，分別是Business logic layer, Data layer(storage)以及Presentations layer(Network)，一層一層去設計後，以SLO及SLI為服務的成長指標，最後會探討如何提升產品的安全性、如何減少開發費用(VMs管控等等)及loadbalance autoscaling設計方法。<br />
lab中大量使用Deploy Managment去部署infrastructure，這些部署的概念必須對GCP有一定的了解，否則會不明白yaml及python檔內的內容<br />
[Week6: Reliable Cloud Infrastructure: Design and Process](https://www.coursera.org/learn/cloud-infrastructure-design-process)<br />
# Feedback
課程雖說需要一個月完成，不過只要花費約兩週的時間就能完成，課程對devops或著是system engineering來說相當的重要，此外課程並非指單一對GCP進行解說，更重要的是雲端服務的設計邏輯，設計方法可不是能在Document內找到答案。<br />
不過要全然了解gcp，還是需要透過實作產品及去看官方的Document，Architecting-with-Google-Cloud-Platform Specialization算是對於想要了解gcp服務新手的painkiller，而非panacea。<br />

還有想要取得google cloud architect證照，修完此specialization是不夠的，但我認為是必須的，課程中並未深入提到k8s engine(google產品主軸)及container技術，因此如果想要入手證照要對k8s有相當程度的了解。
