# Awesome EOSIO Plugins

A curated list of awesome [Eos.io](http://eos.io/) plugins. Inspired by [awesome-go](https://github.com/avelino/awesome-go).

For a generic list of EOSIO resources, visit [awesome-eos](https://github.com/eosplace/awesome-eos/)
### Contributing
Please take a quick gander at the [contribution guidelines](https://github.com/tmuskal/awesome-eosio-plugins/blob/master/CONTRIBUTING.md) first. 

## Queues Plugins:
Push blockchain data into a queue

- [kafka_plugin](https://github.com/TP-Lab/kafka_plugin) - Kafka
- [eos_zmq_plugin](https://github.com/cc32d9/eos_zmq_plugin) - ZeroMQ
- [eos-rabbitmq-plugin](https://github.com/bancorprotocol/eos-rabbitmq-plugin) - RabbitMQ

## DB Plugins:
Sync blockchain data into a DB

- [eosio_sql_plugin](https://github.com/asiniscalchi/eosio_sql_plugin) - SOCI based SQL Databases
- [eos_sql_db_plugin](https://github.com/superoneio/eos_sql_db_plugin) - MySQL Databases
- [elasticsearch_plugin](https://github.com/EOSLaoMao/elasticsearch_plugin) - ElasticSearch

## Push Plugins:
Notify blockchain data to consumers through other protocols:

- [eosio-watcher-plugin](https://github.com/eosauthority/eosio-watcher-plugin) - HTTP POST to endpoint for on chain actions
- [eosio_block_subscription_plugin](https://github.com/MyWishPlatform/eosio_block_subscription_plugin) - TCP Server for push notifications on chain actions

## Debug Plugins
- [eosio_all_code_dump_plugin](https://github.com/spoonincode/eosio_all_code_dump_plugin) - Dump all contract code to a directory

## Block Producer Plugins:
- [eos-producer-heartbeat-plugin](https://github.com/bancorprotocol/eos-producer-heartbeat-plugin) - BP Heartbeat 
- [blacklist_plugin](https://github.com/EOSLaoMao/blacklist_plugin) - Integration with the BP Blacklist contract 

