Kafka client module for Wildfly and JBoss.

Tested with kafka-clients-0.8.2.0 and wildfly 8.2.0.Final.

Copy to module directory to Wildfly or JBoss module directory. Then load it in ```jboss-deployment-structure.xml``` file. Like:

```xml
<jboss-deployment-structure>
    <deployment>
        <dependencies>
            <module name="org.apache.kafka.clients" />
        </dependencies>
    </deployment>
</jboss-deployment-structure>
```
