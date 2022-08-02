# Custom Page Close Opportunity

Welcome to the Custom Page Opportunity Close dialog for Dynamics 365. I always thought the OOTB dialog was extremely booring, so I decided to find a different (and more fun) way to close Opportunities in Dynamics 🙏

My solution contains the following
Tables:
  - Business Unit
    - Custom Fields
      - **Teams ID** <- ID for Team to post about sales
      - **Teams Channel ID** <- ID for Channel to post about sales
    - Custom Form
      - **Business Unit main form** <- Only to show the custom fields above
  - Opportunity
    - Commands
      - **Close as Won** <- Action to close the Opportunity    
  - Web Resources
    - JavaScript
      - **Opportunity Button WIN** <- Javascript to opent he Custom Page    
    - Images
      - **Sales Win Icon** <- Icon for the ribbon bar
  - Component Libraries
    - **SalesWin_DefaultCommandLibrary** <- Ribbon for the application
  
