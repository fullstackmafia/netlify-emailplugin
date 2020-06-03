Netlify Postmark Email Plugin
Email someone when your site has finished successfully deploying.

How to use
In your netlify manifest file add:

name: netlify-emailplugin
inputs:
  - name: from
    description: Sender email
    default: your email here
  - name: to
    description: Receiver email
    default: your recipient's email here


Environment Variables
Add these environment variables to your project:

KEY - Your Postmark API key
FROM_EMAIL - The email address you'll be sending your email from.
TO_EMAIL -  The email address you'll be sending your email to.
