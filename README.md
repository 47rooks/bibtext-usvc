# bibtext-usvc
An experimental REST microservice for accessing biblical text data

## Background
This is a first attempt to design a REST API from scratch spec-first that
can support a true HATEOAS behaviour. A good deal of assistance comes from
Mike Stowe's 'Undisturbed REST'. The API is specified first in
[JSONAPI](http://jsonapi.org).

The initial target implementation is the ETCBC
Text Fabric API. This will enable running queries against the SBLGNT and
ETCBC Hebrew texts via a microservice using REST. If this is successful then
experiments can be made with an implementation on top of Zorba to get XML
data into the mix.
