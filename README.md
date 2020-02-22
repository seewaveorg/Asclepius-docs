## Nginx Web server

https://docs.nginx.com/nginx/admin-guide/installing-nginx/installing-nginx-docker/


Nignx coniguration file.
https://www.nginx.com/resources/wiki/start/topics/examples/full/

```
docker build -t mynginx_image .

// Run the file


docker run --name seenginx -p 80:80 -d mynginx_image

Or to have volumes

docker run --name seenginx -p 80:80 -v /home/tharanga/Documents/SEEWAVE/PROJECTS/material-design-template/content:/usr/share/nginx/html:rw -d mynginx_image



docker run --name mynginx2 -v /var/www:/usr/share/nginx/html:rw



```



## Web site

<h1>Material Design One Page HTML Template</h1>
<p>MD One page template is fully responsive and free to use. This HTML template is based on <a href="http://materializecss.com/">Materialize</a>, a CSS Framework based on Material Design.</p>
<a href="http://joashpereira.com/templates/material_one_pager/">View Demo</a>
<br/>
<h3>Screenshots</h3>
<img src="https://m1.behance.net/rendition/modules/155787441/disp/f7713eb665752f2da380ec8f7a3cdcae.png" height="300px"/> <img src="https://m1.behance.net/rendition/modules/155787447/disp/e546efd70f5b46e45829e0da79375243.png" height="300px"/>
<br/>
<a href="https://www.behance.net/gallery/23484793/Material-Design-One-Page-Template">View More Screens</a>
<h3>Platforms used</h3>
HTML, CSS, JS

<h3>Resources</h3>
<ul>
    <li><a href="http://materializecss.com/">Materialize</a></li>
    <li><a href="http://www.materialpalette.com/">Material Design Colors</a></li>
</ul>

<h2>License</h2>
Material Design One Page HTML Template is licensed under the <a href="http://sam.zoy.org/wtfpl/">WTFPL license</a>.
