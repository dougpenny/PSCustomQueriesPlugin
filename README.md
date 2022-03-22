# PSCustomQueriesPlugin
PSCustomQueriesPlugin is used, along with an API client (like [SwiftyPSCore](https://github.com/dougpenny/SwiftyPSCore) or [PyPowerSchool](https://github.com/dougpenny/PyPowerSchool)), to interact with the PowerSchool API. The plugin does a couple of things:
1. Provides the credentials needed to connect with the PowerSchool API using an API client.
2. Allows you to create custom [PowerQueries](https://support.powerschool.com/developer/#/page/powerqueries), which are SQL statements executed directly on the PowerSchool server.

You can use the plugin as is, or you can modify and add to it as you see fit. To install the plugin, first create a ZIP file containing the `queries_root` directory and the `plugin.xml` file. Then navigate to the Plugin Management Dashboard in PowerSchool and upload the ZIP file.
