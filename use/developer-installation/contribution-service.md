# Contribution Service

### System requirements

<table><thead><tr><th width="323">Softwares / Frameworks</th><th>Version</th></tr></thead><tbody><tr><td>Node</td><td>10x or above</td></tr><tr><td>Postgres</td><td>9.6</td></tr><tr><td>Redis</td><td>4.x or above</td></tr><tr><td>Kafka</td><td>2.4.1</td></tr></tbody></table>

### Installation

The steps to install contribution/program service, are given in here.

{% embed url="https://github.com/Sunbird-Ed/program-service/tree/release-4.8.0#readme" %}

![](../../.gitbook/assets/program\_service.jpg)

### Configuration

<table><thead><tr><th width="150" align="center">S. NO.</th><th width="232">VARIABLE NAME</th><th width="210">DESCRIPTION</th><th>PURPOSE</th><th>DEFAULT</th></tr></thead><tbody><tr><td align="center">1</td><td>dock_base_url</td><td>Represents the co-kreat portal URL</td><td>To connect to the co-kreat portal </td><td>https://dockstaging.sunbirded.org</td></tr><tr><td align="center">2</td><td>sunbird_base_url</td><td>Represents the  sunbirdEd portal URL</td><td>To connect to the sunbird portal </td><td>https://staging.sunbirded.org</td></tr><tr><td align="center">3</td><td>sunbird_service_log_level</td><td>Defines the log level</td><td>To define the log level</td><td>info</td></tr><tr><td align="center">4</td><td>sunbird_api_auth_token</td><td>Represents the auth token to connect APIs</td><td>To connect the services</td><td></td></tr><tr><td align="center">5</td><td>learning_service_url</td><td>Represents the learning service URL</td><td>To connect to the learning service URL</td><td>https://dock.sunbirded.org/action/</td></tr><tr><td align="center">6</td><td>learner_service_url</td><td>Represents the learner service URL</td><td>To connect to the learner service URL</td><td></td></tr><tr><td align="center">7</td><td>content_service_url</td><td>Represents the content service URL</td><td>To connect to the content service URL</td><td>https://dock.sunbirded.org/action/</td></tr><tr><td align="center">8</td><td>opensaber_service_url</td><td>Represents the contribution registry URL</td><td>To connect to the contribution registry service URL</td><td></td></tr><tr><td align="center">9</td><td>sunbird_kafka_host</td><td>Represents the sunbird Kafka host</td><td>To connect to the Kafka server</td><td></td></tr><tr><td align="center">10</td><td>dock_kafka_host</td><td>Represents the coKreat Kafka host</td><td>To connect to the Kafka server</td><td></td></tr><tr><td align="center">11</td><td>dock_redis_host</td><td>Represents the Redis server host</td><td>To connect to the Redis server</td><td></td></tr><tr><td align="center">12</td><td>dock_redis_port</td><td>Represents the Redis server port</td><td></td><td></td></tr><tr><td align="center">13</td><td>sunbird_question_bulkupload_topic</td><td>Defines the default topic to be used for the content created using bulk upload</td><td>Represents the default topic to be used for the content created using bulk upload</td><td></td></tr><tr><td align="center">14</td><td>sunbird_assessment_service_base_url</td><td>Represents the assessment service URL</td><td>To connect to the assessment service URL</td><td></td></tr><tr><td align="center">15</td><td>CORE_INGRESS_GATEWAY_IP</td><td>Ingress IP</td><td>Ingress IP</td><td></td></tr></tbody></table>

