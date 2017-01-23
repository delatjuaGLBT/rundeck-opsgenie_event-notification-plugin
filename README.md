## Rundeck OpsGenie Notification Plugin

### Installation

Copy the groovy script to the plugins directory:

```sh
$ sudo cp OpsGenieEventNotification.groovy /var/lib/rundec/libext/
```

### Configuration

The plugin requires one configuration entry.

* subject: This string will be set as the description for the generated incident.
* api_key: This is the API Key to your OpsGenie API.
