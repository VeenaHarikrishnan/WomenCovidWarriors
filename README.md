# iMatterPlatform - 
Team & Authors:
1.Rashmi Dastidar
2.Nirmala Devidasan
3.Tanya Maheshwari
4.Keerthi Gubba
5.Veena Chandrika

<h1>Overview</h1>

<h2>What's the problem?</h2>

COVID-19, apart from being a pandemic health crisis is a socio economic crisis which has affected people from all sectors of the society.The challenges faced are multifold. iMatter Platform is a humble attempt from us the, Volvo_CO[vi]DE WARRIOR, to battle against an invisible enemy that has disrupted our lives and challenged the normal. 
The working mothers of young children, even those with flexible jobs,are straining under the pressure of round-the-clock “pandemic parenting” and eldercare.And while this situation poses challenges for men, too, it hits women harder.After all, women still undertake the disproportionate share of caregiving responsibilities, and the very infrastructure that makes full-time work possible for many mothers—assistance from relatives, daycare, school—has, for the first time in at least a century, fully shut down in many countries around the world.They are stressed right now about pretty much everything, including how extended school closures will affect their kids’ learning, ensure that the health concerns of the family and self are addressed, without a risk of exposure to the novel corona virus and also continue to support the financial needs of the family while giving back to the society as well.
Teachers also need socio-emotional support to face the pressure being put to deliver learning in a time of crisis as well as support their students’ emotional needs.Online teaching has turned up as a massive shock for both teacher’s productivity and also student’s social life and learning.For the differently abled and for the underprivileged, the impact is even more and every citizen has a moral and social responsibility to ensure that food,education and health remains accessible.Parents, teachers and students also should stay mentally and physically active and healthy.
The world cannot forever, remain under lockdown and we will one day have to open up so that our economy does not collapse. While doing so, we have to ensure that we continue to maintain the social distancing and other best practices we follow today so as to ensure that the society remains unaffected.

<h2>The Technology , Idea and Solution</h2>

It is a RemoteEverything world that we are in today. The iMatter platform digitalizes the health and education activities and also ensure that it remains accessible even to the differently abled and the underpriveleged . Teachers can take online classes, conduct quiz, upload notes, videos , monitor students performance and remotely connect with the parents and students there by ensuring that they stay focused.The Watson assistant can help the users stay informed and connected 24 X 7. Students can make use of the Watson assistant to revise the portions and for self assessment. Watson can also address queries related to health and nutrition.The video transcribe service used helps students to download lecture notes even if they have missed the classes. The multilingual feature which we have added helps students across the nation to make use of the online lectures without language barriers.It also ensures that the differently abled children’s educational needs are addressed. The quiz app will help the teacher to assess the students regularly and parents can monitor their wards progress. A solution which will help maintain social distancing and usage of face masks is also provided which is integrated to a calling functionality so that in case of a violation, an alarm is raised so that necessary actions can be taken. To ensure that the society stays healthy physically and mentally we have linked our application to online health services. We have also ensured that we practice social responsibility and our platform ensures that education remains accessible to all irrespective of their financial background and their location .Our platform makes use of a service which will help collect spare smart devices which can be used by the needy . There is a provision to donate for meals also. Inorder to ensure that women stay empowered our platform provides startup information for the women entrepreneurs in making.
Mobile, web, and cloud services used in our platform enabled rapid deployment of applications that can empower cooperation in the community.

<h2>Architecture Diagram </h2>

<h2>Web:</h2>

![Web Application Architecture](https://user-images.githubusercontent.com/18705108/83942863-1b0f7980-a815-11ea-9109-544ecb143b43.JPG)

<h2>Web Application Workflow</h2>

<h2>Mobile:</h2>

![Mobile Application Architecture](https://user-images.githubusercontent.com/18705108/83942892-5611ad00-a815-11ea-8f28-3b87ef776680.JPG )

<h2>Mobile Application Workflow</h2>

•	User launches the mobile app, enters his/her credentials on the login screen and clicks Login.
•	Mobile app sends the user credentials to MFP server for validation.
•	MFP server invokes the security adapter logic to validate user credentials and returns an appropriate response to the mobile app. For the sake of this demo, we will use a simple security adapter that returns success when password equals username.
•	If user authentication succeeds, mobile app proceeds to show the home page where the tiles for the different roles such as Teacher, Student and Parent are displayed. 
•	For pages like Physician Details, Social Responsibility etc we are using IBM storage and API services. MFP adapter fetches the data from Cloudant and returns it to the mobile app. The data fetched from Cloudant will have references to the images stored in Cloud Object Storage.
•	Backend integration APIs are developed using Citizen Integration capabilities that IBM AppConnect provides to integrate with Google Spreadsheet. 
•	MFP API adapter is used to connect to the public API exposed from IBM AppConnect to retrieve the details.

<h2>IBM Services Used </h2>

IBM Cloud Foundry
IBM Watson Assistant
IBM Watson Discovery
IBM App Connect
IBM NLU
IBM Cloud Object Storage
IBM Cloudant
IBM Digital App Builder (DAB)
Mobile Foundation Server
IBM Watson Studio

<h2>Challenges Faced:</h2>

We have tried to use the IBM Cloud Platform and associated services in our solution to maximum.
The documentation and the enablement sessions provided helped us to shorten the learning curve.
The IBM Digital App Builder made the mobile app development very easy however there were lot of limitations in the tool due to which we had to restrict the scope. We created the ionic app using the IBM DAB and to cover the limitations, we built an app using react native, which incorporated web views, video embedding and so on. We faced some challenges initially on incorporating the Security, REST API & Storage adapters but we were able to overcome it.
We followed the same approach in the Web Application development also & have tried to incorporate maximum IBM provided cloud services.

<h2>References</h2>

IBM Watson Assistant 
How-to guides for chatbots 
Learning path: Getting started with Watson Assistant 
Build a Chatbot for Your Mobile App 
Building successful mobile apps article series

