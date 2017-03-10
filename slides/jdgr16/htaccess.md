<pre style="font-size:12px">

# Comprimir la salida
AddOutputFilterByType DEFLATE text/html text/css text/plain text/xml application/x-javascript application/javascript  text/javascript application/x-font-ttf application/x-font-opentype image/svg+xml
BrowserMatch ^Mozilla/4 gzip-only-text/html
BrowserMatch ^Mozilla/4\\.0[678] no-gzip
BrowserMatch \bMSIE !no-gzip !gzip-only-text/html

# Add correct content-type for fonts
AddType application/vnd.ms-fontobject .eot
AddType application/x-font-ttf .ttf
AddType application/x-font-opentype .otf
AddType application/x-font-woff .woff

ExpiresActive On
ExpiresByType image/png "access plus 12 days"
ExpiresByType image/jpeg "access plus 12 days"
ExpiresByType image/gif "access plus 12 days"
ExpiresByType image/svg+xml "access plus 12 days"
ExpiresByType image/x-icon "access plus 12 days"
ExpiresByType application/x-shockwave-flash "access plus 12 days"
ExpiresByType avideo/mp4 "access plus 12 days"
ExpiresByType text/css "access plus 12 days"
ExpiresByType text/javascript "access plus 12 days"
ExpiresByType application/javascript "access plus 12 days"
ExpiresByType application/x-javascript "access plus 12 days"

# Add a far future Expires header for fonts
ExpiresByType application/vnd.ms-fontobject "access plus 1 year"
ExpiresByType application/x-font-ttf "access plus 1 year"
ExpiresByType application/x-font-opentype "access plus 1 year"
ExpiresByType application/x-font-woff "access plus 1 year"
ExpiresByType image/svg+xml "access plus 1 year"
</pre>
