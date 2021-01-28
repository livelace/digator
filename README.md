# digator

***digator*** ("dig" + "gator") is a set of tools for different [NLP](https://en.wikipedia.org/wiki/Natural_language_processing) tasks.

1. [digator-opennlp](https://github.com/livelace/digator-opennlp) - is an API service for [OpenNLP](https://opennlp.apache.org/) related tasks.
2. [digator-label-studio](https://github.com/livelace/digator-label-studio) - ML backends for [Label Studio](https://github.com/heartexlabs/label-studio). 

#### Case 1. Automatic NER labeling with Label Studio and OpenNLP ML backend:

```shell
git clone https://github.com/livelace/digator /tmp/digator
cd /tmp/digator/case1
docker-compose up
```

Navigate to [http://127.0.0.1:9090](http://127.0.0.1:9090) for Label Studio UI data importing/labeling.

