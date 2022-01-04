# Kafka Search UI Backend

For a limited or selected set of kafka topics, a data pipeline (spark) updates a postgres database with identifier
keys/values and partitions/offsets.

The kafkasearch-ui backend serves an API for a UI, that queries the database, and seeks for the raw kafka message.

### Third-party Resources
* Statically compiled kafkacat docker image from https://github.com/jcaesar/kafkacat-static
* Gofiber: https://github.com/gofiber/fiber

