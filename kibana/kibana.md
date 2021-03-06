# Kibana

### Getting Started
* launch the service
 * `./bin/kibana`

### Access
* 127.0.0.1:5601

### query
* equal(`...==...`), inequal(`!...==...`)
* greater (`...:>...`)

### Data Visualization
##### Getting Started
    * metrics: similar to the **value** of y-axis
    * bucket: similar to the **set** of data of x-axis
##### Aggregation (Supported by Elasticsearch)
    * unique count
    * count
    * max... etc

#### Plugins
* `./bin/kibana plugin --install elastic/sense`
 * 'http://<host:port>/app/sense'

#### Problem
* Cannot use .raw filed in Kibana.
 * [Confused about how to use .raw fields and not analyze string fields](https://discuss.elastic.co/t/confused-about-how-to-use-raw-fields-and-not-analyze-string-fields/28106)
