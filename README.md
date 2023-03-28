#rockywang
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://github.com/Wang-ChihHung/rockywang.git$1 [R,L]
