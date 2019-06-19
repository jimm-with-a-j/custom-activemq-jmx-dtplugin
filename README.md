# custom-activemq-jmx-dtplugin

Demo of how you can customize the a Dynatrace JMX plugin to suit your needs. This one started out based on the built-in ActiveMQ OneAgent plugin. It demonstrates some of the key features you can use and is designed to be as simple as possible only showing the one queue size metric.

You can use the built in JMX editor in Dynatrace to make your own. This does not allow you to use all of the features of JMX plugins but you can use it as a starting point and to see which metrics are available in your app processes.

Alerts you create can be adjusted under Anomaly detection -> plugin events settings.

Note for this you can use a wildcard or specify a pattern for the queue or broker to limit what is collected.

Sources:
https://dynatrace.github.io/plugin-sdk/api/plugin_json_apidoc.html
https://www.dynatrace.com/support/help/extend-dynatrace/plugins/jmx-plugins/
