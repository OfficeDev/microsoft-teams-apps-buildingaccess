---
page_type: sample
products:
- Power Apps
- Power Automate
- SharePoint
description: Power Apps solution that enables organizations to bring employees back into the office facilities safely, as economies and businesses reopen and organizations plan gradual reopening of their office facilities.
urlFragment: microsoft-teams-apps-buildingaccess
---

# Building Access App Template

| [Documentation](https://github.com/OfficeDev/microsoft-teams-apps-buildingaccess/wiki/Home) | [Deployment guide](https://github.com/OfficeDev/microsoft-teams-apps-buildingaccess/wiki/Deployment-Guide) | [Architecture](https://github.com/OfficeDev/microsoft-teams-apps-buildingaccess/wiki/Solution-Overview) |
| ---- | ---- | ---- |

The **Building Access** app can be used by organizations to bring employees
back into the office facilities safely, as economies and businesses
reopen and organizations plan gradual reopening of their office
facilities. Facilities teams globally are working to restructure
building layouts, and seating arrangements to maintain social distancing
norms and control building occupancy thresholds. They need a way to
manage, track and report employee onsite presence.

Built using Power Apps, Power Automate, Power BI, and SharePoint Online
with deep integrations with Microsoft Teams*, the **app allows
facilities managers to manage facility readiness**, **define occupancy
thresholds** per floor or open space in a building, **set eligibility
criteria** for onsite access **and allows employees to reserve an office
workspace after providing self-attestation on key health questions**.
Executives and facility managers can use the **included Power BI
dashboard to gather insights** needed for planning purposes.

<!-- a normal html comment ![A screenshot of the Building Access Home Screen](.//media/image1.png)  -->

The solution is suite of **three** **apps** - **Building Access** app
for employees and managers, **Building Admin** app for facilities teams
and **Building Security** app for security teams, thereby servicing the
needs of multiple personas.

 

<!-- ![A screenshot of the various personas supported by the App](.//media/image2.jpeg)  -->

 

While the app comes with several innovative features, we hope it is easy
for you to extend, enhance and adapt it for your needs since this is
built using our low-code Power Platform. The app has several
configuration settings that can be leveraged to customize the solution
without any code changes.

Here are a few key features:

-   As facilities teams get buildings ready for onsite access, they can configure buildings in the system once they are ready and control capacity on a building and floor (or open space) level. The capacity can be updated as you ramp up onsite work.

-   We understand approving onsite access requests for thousands or even hundreds of workers is going to be a huge overhead for your already stretched workforce. The app offers an easy to use dial to control auto approvals vs manager approvals so facilities teams can establish the optimal setting for their organization. For example, the Auto-Approval Threshold setting of 0% would turn off auto approvals and send every request to the manager for approval, while a setting of 75% would auto approve the initial 75% requests if the key eligibility criteria are met and only require managers to approve the last 25%.

-   Managers are notified via an adaptive card in Teams when a new request in submitted and they can approve or reject the request directly from Teams ensuring minimum disruption for them. They can also do bulk approvals from the app.

-   We know that a one-size solution doesn't work for everyone and organizations would need to define a key eligibility questionnaire based on their requirements. You can define key eligibility questions or turn off the feature completely using the Building Admin companion app.

-   For emergency approvals, the security team can initiate a 1x1 chat with the direct manager from the approval screen in the Building Security app allowing them to collaborate with the managers directly and expedite process.

-   Security teams can leverage the companion Building Security app to get a quick snapshot of the people approved, already onsite and pending check-ins for any building

-   Facilities teams can use the Power BI dashboard to check current and projected occupancy levels and use the contact tracing report to identify people that were present at the same time and in the same building as another individual

Please check the [detailed deployment guide](ToDo) that walk through the steps for deploying the app in your environment. The instructions cover:

-   Creating a location for your data
-   Running a Power Automate to create the SharePoint lists
-   Importing and configuring the Building Access App
-   Importing and configuring the Building Admin App
-   Importing and configuring the Building Security App
-   Configuring the App settings and creating initial content
-   Deploying the App to Teams
-   Configuring the PowerBI Dashboard
  

## Legal notice

This app template is provided under the [MIT License](https://github.com/OfficeDev/microsoft-teams-apps-buildingaccess/blob/master/LICENSE) terms.  In addition to these terms, by using this app template you agree to the following:

- You, not Microsoft, will license the use of your app to users or organization. 

- This app template is not intended to substitute your own regulatory due diligence or make you or your app compliant with respect to any applicable regulations, including but not limited to privacy, healthcare, employment, or financial regulations.

- You are responsible for complying with all applicable privacy and security regulations including those related to use, collection and handling of any personal data by your app. This includes complying with all internal privacy and security policies of your organization if your app is developed to be sideloaded internally within your organization. Where applicable, you may be responsible for data related incidents or data subject requests for data collected through your app.

- Any trademarks or registered trademarks of Microsoft in the United States and/or other countries and logos included in this repository are the property of Microsoft, and the license for this project does not grant you rights to use any Microsoft names, logos or trademarks outside of this repository. Microsoft’s general trademark guidelines can be found [here](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general.aspx).

- If the app template enables access to any Microsoft Internet-based services (e.g., Office365), use of those services will be subject to the separately-provided terms of use. In such cases, Microsoft may collect telemetry data related to app template usage and operation. Use and handling of telemetry data will be performed in accordance with such terms of use.

- Use of this template does not guarantee acceptance of your app to the Teams app store. To make this app available in the Teams app store, you will have to comply with the [submission and validation process](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/deploy-and-publish/appsource/publish), and all associated requirements such as including your own privacy statement and terms of use for your app.


## Getting started

Begin with the [Solution overview](https://github.com/OfficeDev/microsoft-teams-apps-buildingaccess/wiki/Solution-overview) to read about what the app does and how it works.

When you're ready to try out Building Access app, or to use it in your own organization, follow the steps in the [Deployment guide](https://github.com/OfficeDev/microsoft-teams-apps-buildingaccess/wiki/Deployment-guide).

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
