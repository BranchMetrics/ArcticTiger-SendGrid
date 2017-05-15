Any use of the visual editor in SendGrid will break the template and prevent Branch links from working. To edit the template it is necessary to do the following:

## 1. Update the sendgrid.html file  

  - To edit: https://github.com/BranchMetrics/ArcticTiger-SendGrid/blob/master/sendgrid.html 
  - To preview changes: https://branchmetrics.github.io/ArcticTiger-SendGrid/sendgrid.html 

## 2. Update the SendGrid Default Template.

### In the SendGrid dashboard: 
  1. Templates > Transactional 
  2. Actions > Edit 
  3. IMPORTANT: Drag and drop editor: OFF 
  4. Select the "<> CODE" toggle at the top of the screen 
  5. Paste in the text from https://github.com/BranchMetrics/ArcticTiger-SendGrid/blob/master/sendgrid.html 
  6. Click the "Save Template" button 

## 3. Send a test message
  1. Templates > Transactional
  2. Actions > Preview & Test
  3. Click on the Send Test button
  4. There are currently five Journey templates available, for which I've created and started five different Journeys. I've listed the full URLs for each active Journey here:

  - https://github.com/BranchMetrics/ArcticTiger-SendGrid/blob/master/index.html

To specify use of a new Journery in a link you append the Journey name to the following URL:

  - https://branchmetrics.github.io/ArcticTiger-SendGrid/redirect.html?journey=
