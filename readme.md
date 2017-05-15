Any use of the visual editor in SendGrid will break the template and prevent Branch links from working. To edit the template it is necessary to do the following:

# - Update the sendgrid.html template  

To edit: https://github.com/BranchMetrics/ArcticTiger-SendGrid/blob/master/sendgrid.html

To preview changes: https://branchmetrics.github.io/ArcticTiger-SendGrid/sendgrid.html

# - Update the SendGrid Default Template  

In the SendGrid dashboard: 
 # Templates > Transactional 
 # Actions > Edit 
 # IMPORTANT: Drag and drop editor: OFF 
 # Select the "<> CODE" toggle at the top of the screen 
 # Paste in the text from https://github.com/BranchMetrics/ArcticTiger-SendGrid/blob/master/sendgrid.html 
 # Click the "Save Template" button 

# - Send a test message
 # Templates > Transactional
 # Actions > Preview & Test
 # Click on the Send Test button
 # There are currently five Journey templates available, for which I've created and started five different Journeys. I've listed the full URLs for each active Journey here:

https://github.com/BranchMetrics/ArcticTiger-SendGrid/blob/master/index.html

To specify use of a new Journery in a link you append the Journey name to the following URL:

https://branchmetrics.github.io/ArcticTiger-SendGrid/redirect.html?journey=
