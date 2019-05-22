# Deprecation of Unified service desk 3.2 and lower versions, and features

To help provide the best possible Unified Service Desk experiences, we recently announced the General Availability of Unified Service Desk 4.1, delivering improved performance and a host of feature enhancements.

Below you’ll find information about the versions and features that have been marked as deprecated with the latest release of Unified Service Desk 4.1. Administrators and IT professionals should use this information to prepare for future releases of Dynamics 365 Unified Service Desk.

What is deprecation?  

Deprecation means we intend to remove the feature or capability from a future major release of Unified Service Desk. The feature or capability continues to work until the next major release, and ultimately, these features will be removed from the product in our next major release. This process gives customers at least one release cycle to adapt their implementation to a newer version of a deprecated capability, before actual removal.

List of deprecated features/capabilities from Unified Service Desk
1.) Unified Service Desk 3.2 and any lower versions 

Unified Service Desk has an annual release cadence for the major version upgrades. We encourage you to be on the latest version and take advantage of the new features/capabilities and enhancements.  Customers on Unified Service Desk 3.2 or a lower version, should plan to migrate to the latest/supported release of Unified Service Desk.

Going forward, Unified Service Desk will support the last three releases (N-2 format). On the release of the next version of Unified Service Desk, the oldest supported version will be deprecated. For example, with the release of Unified Service Desk 4.2, Unified Service Desk 3.3 version will stand deprecated.

 2.) Hosted controls

Hosted Control and Web Hosted Application of CCA Hosted Application 
For the CCA Hosted Application type of hosted control, there are four types of Hosted App Type. Out of those, Hosted Control and Web Hosted Application are depreciated. If you are using Hosted Control Hosted App Type of CCA Hosted Application, use the USD Hosted Control type of hosted control. Similarly, for Web Hosted Application Hosted App Type, use the Standard web application type of hosted control. Web Hosted Application uses the paradigm of UII Web Application Adapter (UII action protocols) to talk and interact with Unified Service Desk. With the direction to use the Standard web application type of hosted control, we recommend you to use RunScript actions.
 

CRM Dialog hosted control  
The CRM Dialog hosted control type is used to work with Dynamics 365 for Customer Engagement apps dialog. As Dialogs are deprecated, we are deprecating CRM Dialog hosted control.  As an alternative to Dialogs, you can use Business Process Flows or Canvas Apps. In Unified Service Desk, you can use Unified Interface page or Standard Web Application type of hosted control. For more information see,  Dialogs are deprecated.
 

Interactive Service Hub Page hosted control 
The Interactive Service Hub Page hosted control is used to host interactive service hub forms within Unified Service Desk. If you are using this hosted control type, upgrade to Unified Interface forms and use Unified Interface Page hosted control.