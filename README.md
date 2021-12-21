# reactive-cloud-stream
REST and Spring Cloud Stream examples using Functional Components.

You can use the following request to send messages.

```
curl --location --request POST 'http://localhost:8010/messages' \
--header 'Content-Type: application/json' \
--data-raw '{
    "content" : "This is the message content."
}'
```

Here is the introducing to Functions for Spring Cloud Stream [Functions for Spring Cloud Stream](https://spring.io/blog/2020/07/13/introducing-java-functions-for-spring-cloud-stream-applications-part-0).
