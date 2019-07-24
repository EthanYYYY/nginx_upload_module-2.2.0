# nginx_upload_module-2.2.0
Fix some bugs in nginx_upload_module-2.2.0£º

<blockquote>/opt/package/nginx_upload_module-2.2.0/ngx_http_upload_module.c:14:10: fatal error: md5.h: No such file or directory
 #include <md5.h>
          ^~~~~~~
compilation terminated.
objs/Makefile:1549: recipe for target 'objs/addon/nginx_upload_module-2.2.0/ngx_http_upload_module.o' failed
make[1]: *** [objs/addon/nginx_upload_module-2.2.0/ngx_http_upload_module.o] Error 1
make[1]: Leaving directory '/opt/package/nginx-1.16.0'
Makefile:8: recipe for target 'build' failed
make: *** [build] Error 2</blockquote>

