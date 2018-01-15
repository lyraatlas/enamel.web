   This is how you can console log something during the build process.
   
   
       <%= console.dir(config.menu) %>

whenever you want to change something to gold use this color:   color: rgb(190, 150, 86);


actual change

<% if (page.path.indexOf('archives') > -1) { %>
<%- partial('archivesLayout') %>
<% } else if (page.path.indexOf('contact') > -1) { %>
<%- partial('contactLayout') %>
<% } else if (page.path.indexOf('about') > -1) { %>
<%- partial('aboutLayout') %>
<% } else { %>
<%- partial('layout') %>
<% } %>