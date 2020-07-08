# Shorten URLS with now.json - Vercel

## `What is URL shortener?`
### <li>URL shortener is a service/technique that can take long URLs and convert into substantially shorter user-defined URLs that still directs to the requested page/resource.

## `Why do we need URL shortener?`
### 
<li>Among many reasons, the common reason for a developer to shorten URL is to share a prototype developed with others having a readable URL.
<li>Also, you may want an URL shortener for your custom domain and do not want to pay every year for each one of them.
<li>URL shortener is an easy way to create and update URLs.

## `Steps to configure now.json`

<li>npm i -g now - Install now globally
<li>now login - Authenticate with the now CLI
<li>Create a project directory
<li>npm init - Initialize the project
<li>Create a now.json file
<li>Add the Vercel version 
<li>Create a redirects array
<li>Each object in this redirects array has two keys - source and destination
<li>now - To deploy, hit this cmd
<li>CLI will output 2 URLs
<li>Anytime you want to add or modify the redirect URLs, just modify the now.json
<li>Add a domain name in Vercel and you can link all redirects with your domain name followed by a key-word