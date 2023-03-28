#rockywang
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://Wang-ChihHung.github.com/rockywang.html$1 [R,L]
