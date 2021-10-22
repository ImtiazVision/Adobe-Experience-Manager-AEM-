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

**OSGi technology** : is made up of a collection of standards, implementations for each specification, and test compatibility kits for each specification, all of which work together to establish a dynamic module system for Java. OSGi is a standards-based solution to modularizing Java software applications and infrastructure that is vendor-independent.

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

A servlet engine is an application server that provides the infrastructure for running Java servlets.
When AEM is deployed via the standalone quickstart jar file, it includes a **built-in servlet engine** (CQSE) that operates as a bundle within the OSGi framework.

**Workflow Engine** - Workflows can be used inside CQ WCM to regulate the process of generating and publishing material, which is frequently subject to organizational processes, such as approval and sign-off by multiple participants.

**CQ Components** - Components provide the logic (code) for rendering content. Various OOB components are available; based on our surroundings, we can change these or create new ones.

**CQ Widgets Library** is a proprietary ExtJs library that includes a variety of widgets that may be linked to components for user interaction.

**Apache Sling** is a web application framework used to store and manage content in content repositories such as Apache Jackrabbit or CRX.

**OSGi (Apache Felix)** - CQ is built with the Java OSGi dynamic module framework. This enables various components of CQ to be paused, updated, and restarted without halting the entire system.


## AEM Technology Stack :

**Adobe Experience Manager (AEM)** : is a Java web application that requires a Java Runtime Environment on the server side (JRE). The following are the tech stack of **AEM**:

   1. **Java Platform** : Java Runtime Environment (JRE 1.6 minimum. JRE 1.7 is recommended)
   2. **Granite Platform** (runs on JRE)
        - OSGi Framework (encapsulates all subsequent elements)
        - CQSE Servlet Engine (optional external application server)
        - CRX Content Repository
        - Sling Content Repository
        - Granite UI
   3. **Adobe Experience Manager** (runs on Granite platform, within OSGi framework)
        - Individual AEM modules (WCM, DAM, Workflow, etc.)
   4. **Customer Application** (run on AEM)
        - Customer specific applications (websites, etc. also run within OSGi framework) 

![image](https://user-images.githubusercontent.com/50087271/137973509-e8d1c737-4186-40b7-846c-d721ada14229.png)

## OSGi Framework : 

**OSGi Framework** : is a collection of specifications that allows us to create an application by combining a number of separate re-usable components (programs/codes).

**Advantage of OSGi Framework** :
   - We can add a component without knowing anything about the other components.
   - At runtime, we can uninstall a component.
   - We can dynamically install, start, and stop the application without having to shut it down and restart it.

Aside from the OSGi framework, all other AEM components, as well as any additional custom applications written on top of the AEM platform, are implemented as OSGi bundles.

**Apache Felix** is a collaborative effort to implement the OSGi Framework. The Apache Felix Web Management Console serves as the foundation for AEM's web console.

## Sling Overview 

Sling is a web application framework based on Representational State Transfer (REST) principles that allows for the rapid construction of content-oriented applications that employ a JCR repository, such as Apache Jackrabbit, or, in the case of AEM, the CRX Content Repository, as their data store.

Sling is content-centric, which means that processing is centered on the content, as each (HTTP) request is mapped into content in the form of a JCR resource (a repository node).

## Sling Content Delivery :

RESTful Sling implements a REST-oriented server, introducing a new concept to the web application framework.

The benefits are as follows:
    - Its resources and representations are accurately modeled within the server.
    - Disposes of one or more data models.
    - URL structure, business objects, and DB schema were replaced by URL, resource, and JCR structures.

## Sling Post Servlet :

The Sling Post Servlet is used to make changes to material in a JCR repository. Sling Post Servlet allows us to create, change, copy, move, remove, and import resources.

## CRX Content Repository : 

All data in AEM is saved in the **built-in CRX** content repository, which is a Java Content Repository Specification implementation (JCR).


JCR Content Repository has the following features:

- The AEM repository is known as CRX.
- Adobe's implementation of the Content Repository Specification for Java Technology 2.0 is known as CRX.
- The specification is commonly abbreviated as JCR. JCR denotes the type of repository; for example, CRX.
- **Apache Jackrabbit** is another example of a JCR repository. Jackrabbit is the JCR reference implementation.
- CRX, while technically a different specification implementation, is built on the Jackrabbit codebase.

### What we learned so far : 

The OSGi Framework allows us to create applications by building many independent re-usable components (programs/codes).


Sling Content Delivery, which demonstrates best practices and incorporates UI concepts.


The CRX Content Repository is where all of AEM's data is stored.


When AEM is deployed using the standalone quickstart jar file, the Servlet Engine runs as a bundle within the OSGi framework.

## AEM Installation : 

The OSGi Framework allows us to create applications by building many independent re-usable components (programs/codes).


Sling Content Delivery, which demonstrates best practices and incorporates UI concepts.


The CRX Content Repository is where all of AEM's data is stored.


When AEM is deployed using the standalone quickstart jar file, the Servlet Engine runs as a bundle within the OSGi framework.

An instance is a clone of AEM that is running on a server in AEM terminology. AEM setups normally involve at least two instances, which are often run on separate machines:

- **Author**: An AEM instance used to create, upload, and edit content, as well as to manage the website.


- **Publish**: An AEM instance that serves the public with the published content.


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

**Component hierarchies** : determine how components share information with one another. There are 3 types of Component Hierarchies :

1. **Resource Type Hierarchy** : Components use it to inherit scripts, dialogs, and descriptions, as well as thumbnail pictures and icons, from the main component.
2. **Container Hierarchy** : is used to transport configuration settings, control set layout, and dialog layout from parent to child components.
3. **Include Hierarchy** : serves as a foundation for many rendering design characteristics such as layout information, CSS information, and the available components in a paragraph system. The sequence of includes imposes this at runtime.



We may use **website design** to provide a consistent appearance and feel across all pages.
