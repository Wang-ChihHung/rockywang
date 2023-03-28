#rockywang
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://Wang-ChihHung.github.io/rockywang/index.html$1 [R,L]
