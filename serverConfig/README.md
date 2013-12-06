GitProject
==========

JBoss 7.1 Runtime Server:

Program arguments:

-mp "/home/victor/_DATA_/jboss-as-7.1.1.Final/modules" -jaxpmodule javax.xml.jaxp-provider org.jboss.as.standalone -b localhost --server-config=standalone.xml


VM Arguments:

-server -Xms64m -Xmx512m -XX:MaxPermSize=256m -Djava.net.preferIPv4Stack=true -Dorg.jboss.resolver.warning=true -Dsun.rmi.dgc.client.gcInterval=3600000 -Dsun.rmi.dgc.server.gcInterval=3600000 -Djboss.modules.system.pkgs=org.jboss.byteman -Djava.awt.headless=true "-Dorg.jboss.boot.log.file=/home/victor/_DATA_/jboss-as-7.1.1.Final/standalone/log/boot.log" "-Dlogging.configuration=file:/home/victor/_DATA_/jboss-as-7.1.1.Final/standalone/configuration/logging.properties" "-Djboss.home.dir=/home/victor/_DATA_/jboss-as-7.1.1.Final" -Xrunjdwp:transport=dt_socket,address=8787,server=y,suspend=n

