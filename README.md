# kibana

# What is Kibana?

Kibana is an open source analytics and visualization platform designed to work with Elasticsearch.

> [www.elastic.co/products/kibana](https://www.elastic.co/products/kibana)

# How to use this image

Run `elasticsearch`:

    docker run -d --name elasticsearch elasticsearch:1.5.0

Run `kibana`:

    docker run -d --name kibana --link elasticsearch:elasticsearch -p 80:5601 madron/kibana
