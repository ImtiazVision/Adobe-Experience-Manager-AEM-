# Adobe-Experience-Manager-AEM-

## Module 1 :

**Web Content** : is a content on the internet, whether it is a full website, a web page, or web page building components such as HTML, JSP,.ASP, PHP, CSS, JavaScripts, Images, Videos, Audios, Flash, Word Docs, PDF files as links, WCM Tool content, and so on.

**WCM (Web Content Management System)**: is a software program that is used to create and manage web content and can be used to build a web application. It enables businesses to alter and evaluate website pages without relying on IT, cutting the time it takes to update product pages from a few days to one hour.
<!-- It is a web application that can be used to create and manage web content. -->

WCM's key features include document control, auditing, editing, and timeline management.

**Features of WCM** : Web Content Management (WCM) key capabilities include document control, auditing, editing, and timeline management. WCM has the following unique features:
- **Authoring Interface** : enables us to build web pages by utilizing templates and components.
- **Version Control** : enables us to retrieve earlier versions and resume work from a certain point.
- **Document Classification** : enables us to manually or automatically tag and categorize metadata (data that characterizes a document).
- **Lifestyle Management** : allows us to keep track of document stages like reviewed, approved, published, archived, and retired.
- **Preview** : During the authoring process, it allows us to view the output of the web page without deploying it to another environment.
- **WorkFlow** : enables us to automate business processes related to the creation, approval, and distribution of web content.
- **Deployment** : enables us to manually or automatically deploy an entire website or a page to runtime environments (Scheduled)
- **Multilingual** : enables us to display content in a variety of languages.
- **Multi Channel Delivery/Mobility** : allows us to change the content and layout of the web page based on the device that is requesting it.
- **Bulk Import** : It enables us to upload files one at a time.
- **Access Control** : enables us to access content based on predefined permissions.
- **Targeting** : enables us to display content based on the logged-in user's profile.
- **Digital Asset Management(DAM)** : enables us to store digital assets such as images, audio, and video files in a single repository and then render them according to specifications.
- **A/B Testing** : gives us the ability to support A/B testing ( Multi Variant Testing).
- **Web Analytics** : enables us to examine website traffic and user behavior.
- **Campaign Management** : helps us to design campaigns for the speedier promotion of Marketing concepts.

**Users of WCM** : 
- **Business Users** : Content Contributors/Authors, Content Reviewers, Content Editors, System Analysts.
- **Developers** : are people who produce Templates, Components, and other components that we can utilize to make web pages.
- **Administrators** : are individuals who ensure that the application is operational, offer access to the authoring environment, and apply patches/perform updates.

**Products of WCM** :
- **AEM Hub** : It is an Adobe WCM solution. Day CQ was purchased by Adobe in 2010. Adobe AEM is the current brand name (Adobe Experience Manager).
- **Sitecore** : Sitecore Experience Platform is the name under which it is now being marketed.
- **SDL Tridion** : SDL bought Tridion, which is now marketed as SDL Tridion.
- **Leading Opensource WCM Products** : Alfresco, Drupal, and Life Ray. 
- **Legacy WCM Products** : Open text Vignette, EMC Web Publisher. 

## Adobe Experience Manager (AEM) Basics : 
**AEM (Adobe Experience Manager)**: is a Web Content Management system that allows you to organize, manage, and deliver creative assets. It is an enterprise-level web content management system with a plethora of strong capabilities such as authoring, publishing, site development, and administration.

**AEM** offers templates for creating targeted content and securely publishing it in the cloud.It is a Java web application which requires a server-side Java Runtime Environment (JRE).

**Adobe Marketing Cloud** : is a comprehensive marketing solution from Adobe Systems that includes a set of integrated online marketing and web analytics solutions. Marketers may use it to monitor, customize, and optimize marketing campaigns and digital experiences for maximum marketing effectiveness.
- **Adobe Analytics** : enables us to obtain real-time information across online and offline platforms, allowing us to continuously improve the performance of marketing initiatives.
- **Adobe Social** : assists us in managing social marketing by providing a comprehensive platform that allows for social listening, publishing, and analytics.
- **Adobe Media Optimizer** : assists us in forecasting and optimizing our media mix to achieve the most return on investment (ROI).
- **Adobe Target** : aids us in testing and targeting digital experiences in order to maximize business outcomes.
- **Adobe Campaign** : aids us in the planning and execution of coordinated campaigns across all media.
- **Adobe Experience Manager** : assists us in organizing, managing, and delivering creative assets and other content across several digital marketing channels.

## AEM 6.X Application Stack : 

![image](https://user-images.githubusercontent.com/50087271/137963868-85dde0b6-ced7-4d2b-bbd1-897d23c53c23.png)

## AEM 6.X New Features :
- **New Repository Foundation**
- **Jackrabbit Oak(CRX 3)** : improves the content repository's performance and scalability.
-  The following microkernel storage options are available: 
    - **TarMK (default)** : which stores data using the Tar persistence mechanism.
    - **MongoMK** : which uses Mongo DB for data storage. 
- **Touch UI** : is a new touch-optimized interface developed by Coral UI and based on JQuery.
- **Sightly** : is an HTML templating language that was first introduced with AEM 6.0. It replaces JSP (Java Server Pages) and ESP (ECMAScript Server Pages) as the primary HTML templating solution. The term 'Sightly' (meaning 'pleasant to the eye') emphasizes its emphasis on keeping our markup beautiful, and hence maintainable, once dynamically generated.
- **Social Communities** : enables us to save material on the Adobe Social Cloud.
- **Mobile Apps support** : Using PhoneGap Build, we can manage and deliver mobile apps to various platforms.
- **DAM enhancements** : features two-way syncing with Creative Cloud, Dynamic Media support built right into AEM, processing profiles, metadata schemas, increased search, and improved team collaboration with projects, workflows, and tasks.
- **Operations Dashboard** : enables us to monitor and diagnose the AEM platform as well as perform maintenance activities and other health checks from a single location.
- **Adaptive Forms** : enables us to design sophisticated and dynamic forms.
- **No Automatic Indexes** : It enables us to construct custom indexes as needed.

## Module 2 :

**Viewing and Updating CRX Repository** : 

CRX Explorer allows you to view and update the CRX repository. `[http://localhost:4502/crx/explorer](http://localhost:4502/crx/explorer)` 

**Developing Content using CRXDE Lite Interface** : 

**CRXDE Lite** allows you to perform standard development tasks. It is recommended to use this interface when there is no direct access to the AEM/CRX server. 

**Asset** is a digital asset management tool that is fully integrated with the AEM platform and enables our enterprise to share and distribute digital assets. It is also known as **DAM (Digital Asset Manager)**.

**Working with AEM Tags** : 

**Namespace** is a class of elements like addresses, file locations, etc., in which each element has a name unique to that class, although it may be shared with elements in other classes.

**Tags** which can be applied by authors and site visitors are grouped into various namespaces. Such hierarchies allow taxonomies to be built and these taxonomies are global throughout AEM.

**Leaf tag** is a tag that doesn't have child tags. 

## Module 3 :

A project is an AEM file that contains various elements needed to build our website.


Templates, components, OSGi bundles, and static files are the four components of a project.


An AEM project requires a project structure to allow for easy interaction of elements.

**Templates** : defines the scope for storing content. 

**Components** : implements specific functionalities to deliver content in AEM. 

**OSGi Bundles** : implements the functionalities of OSGi components and AEM components.

**Static Files** : deliver static content on the website/webpage. 

A website **template** is a pre-defined web page that allows us to put in our material and construct our own website.
**Components** are modular, reusable pieces that implement specialized functionality to render content on our website. Every component is a collection of scripts, such as JSPs and JAVA servlets, that perform a certain function.
AEM Components Characteristics:

- There are no hidden configuration files in this package.
- Other Components can be included and operated anywhere within CQ5 or in isolation (e.g. portal).

**Component hierarchies** determine how components share information with one another. There are 3 types of Component Hierarchies, 
1. **Resource Type Hierarchy** : Components use it to inherit scripts, dialogs, and descriptions, as well as thumbnail pictures and icons, from the main component.
2. **Container Hierarchy** : is used to transport configuration settings, control set layout, and dialog layout from parent to child components.
3. **Include Hierarchy** : serves as a foundation for many rendering design characteristics such as layout information, CSS information, and the available components in a paragraph system. The sequence of includes imposes this at runtime.



We may use **website design** to provide a consistent appearance and feel across all pages.
