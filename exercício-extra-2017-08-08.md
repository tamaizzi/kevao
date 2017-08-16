# Histórico de versões do Servidor Apache (HTTP Server Project)

Versão 2.0 > 
https://svn.apache.org/viewvc/httpd/httpd/branches/2.0.x/CHANGES?view=markup

Versão 2.2 > 
https://svn.apache.org/viewvc/httpd/httpd/branches/2.2.x/CHANGES?view=markup

Versão 2.4 > 
https://svn.apache.org/viewvc/httpd/httpd/branches/2.4.x/CHANGES?view=markup

# Histórico de Versões NGINX

Versão 0.0.1 > 
https://rubygems.org/gems/nginx/versions/0.0.1
Versão 0.0.2 > 
https://rubygems.org/gems/nginx/versions/0.0.2

# NGINX > 1.13.4                                        08 Agosto 2017
#
#   *) Feature: the ngx_http_mirror_module.
#
#    *) Bugfix: client connections might be dropped during configuration
#       testing when using the "reuseport" parameter of the "listen"
#       directive on Linux.
#
#    *) Bugfix: request body might not be available in subrequests if it was
#       saved to a file and proxying was used.
#
#    *) Bugfix: cleaning cache based on the "max_size" parameter did not work
#       on Windows.
#
#    *) Bugfix: any shared memory allocation required 4096 bytes on Windows.
#
#    *) Bugfix: nginx worker might be terminated abnormally when using the
#      "zone" directive inside the "upstream" block on Windows.
#
#
#  NGINX > 1.13.3                                        11 Julho 2017
#
 #   *) Security: a specially crafted request might result in an integer
  #     overflow and incorrect processing of ranges in the range filter,
   #    potentially resulting in sensitive information leak (CVE-2017-7529).
#
#
#  NGINX > 1.13.2                                        27 Junho 2017

 #   *) Change: nginx now returns 200 instead of 416 when a range starting
  #     with 0 is requested from an empty file.
#
#    *) Feature: the "add_trailer" directive.
 #      Thanks to Piotr Sikora.
#
 #   *) Bugfix: nginx could not be built on Cygwin and NetBSD; the bug had
  #     appeared in 1.13.0.

   # *) Bugfix: nginx could not be built under MSYS2 / MinGW 64-bit.
      # Thanks to Orgad Shaneh.

    # *) Bugfix: a segmentation fault might occur in a worker process when
       # using SSI with many includes and proxy_pass with variables.

    # *) Bugfix: in the ngx_http_v2_module.
      # Thanks to Piotr Sikora.


# NGINX > 1.13.1                                        30 Maio 2017

 #   *) Feature: now a hostname can be used as the "set_real_ip_from"
  #     directive parameter.

   # *) Feature: vim syntax highlighting scripts improvements.

    # *) Feature: the "worker_cpu_affinity" directive now works on DragonFly
     #  BSD.
      # Thanks to Sepherosa Ziehau.

    # *) Bugfix: SSL renegotiation on backend connections did not work when
       # using OpenSSL before 1.1.0.

    # *) Workaround: nginx could not be built with Oracle Developer Studio
     #  12.5.

    # *) Workaround: now cache manager ignores long locked cache entries when
     #  cleaning cache based on the "max_size" parameter.

   # *) Bugfix: client SSL connections were immediately closed if deferred
    #   accept and the "proxy_protocol" parameter of the "listen" directive
     #  were used.

    # *) Bugfix: in the "proxy_cache_background_update" directive.

    # *) Workaround: now the "tcp_nodelay" directive sets the TCP_NODELAY
     #  option before an SSL handshake.


#  NGINX > 1.13.0                                        25 Abril 2017

 #   *) Change: SSL renegotiation is now allowed on backend connections.

  #  *) Feature: the "rcvbuf" and "sndbuf" parameters of the "listen"
   #    directives of the mail proxy and stream modules.

    # *) Feature: the "return" and "error_page" directives can now be used to
     #  return 308 redirections.
      # Thanks to Simon Leblanc.

    # *) Feature: the "TLSv1.3" parameter of the "ssl_protocols" directive.

    # *) Feature: when logging signals nginx now logs PID of the process which
       sent the signal.

#    *) Bugfix: in memory allocation error handling.

 #   *) Bugfix: if a server in the stream module listened on a wildcard
  #     address, the source address of a response UDP datagram could differ
   #    from the original datagram destination address.
   


# Histórico de Versões WordPress

# 02/Agosto/2017	WordPress 4.8.1 Maintenance Release > https://wordpress.org/news/2017/06/evans/

# 08/Junho/2017	WordPress 4.8 “Evans” > https://wordpress.org/news/2017/08/wordpress-4-8-1-maintenance-release/

# 01/Junho/2017	WordPress 4.8 Release Candidate 2 > https://wordpress.org/news/2017/06/wordpress-4-8-release-candidate-2/

# 25/Maio/2017	WordPress 4.8 Release Candidate

# 23/Maio/2017	WordPress 4.8 Beta 2

# 16/Maio/2017	WordPress 4.7.5 Security and Maintenance Release

# 13/Maio/2017	WordPress 4.8 Beta 1

# 20/Abril/2017	WordPress 4.7.4 Maintenance Release

# 06/Março/2017	WordPress 4.7.3 Security and Maintenance Release

# 26/Janeiro/2017	WordPress 4.7.2 Security Release

# 11/Janeiro/2017	WordPress 4.7.1 Security and Maintenance Release

# 06/Dezembro/2016	WordPress 4.7 “Vaughan”

# 24/Novembro/2016	WordPress 4.7 Release Candidate

# 16/Novembro/2016	WordPress 4.7 Beta 4

# 11/Novembro/2016	WordPress 4.7 Beta 3

# 4/Novembro/2016	WordPress 4.7 Beta 2

# 28/Outubro/2016	WordPress 4.7 Beta 1

# 7/Setembro/2016	WordPress 4.6.1 Security and Maintenance Release

# 16/Agosto/2016	WordPress 4.6 “Pepper”

# 11/Agosto/2016	WordPress 4.6 RC2

# 27/Julho/2016	WordPress 4.6 Release Candidate
