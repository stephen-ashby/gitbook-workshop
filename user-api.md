---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# User API

Welcome to the User API documentation. This guide provides all the information you need to interact with our API, including endpoints, request/response structures, and usage examples. By following this documentation, you will be able to seamlessly integrate our user management features into your application.

{% swagger src=".gitbook/assets/openapi.json" path="/user" method="post" %}
[openapi.json](.gitbook/assets/openapi.json)
{% endswagger %}

{% swagger src=".gitbook/assets/openapi.json" path="/user/createWithList" method="post" %}
[openapi.json](.gitbook/assets/openapi.json)
{% endswagger %}

{% swagger src=".gitbook/assets/openapi.json" path="/user/login" method="get" %}
[openapi.json](.gitbook/assets/openapi.json)
{% endswagger %}

{% swagger src=".gitbook/assets/openapi.json" path="/user/logout" method="get" %}
[openapi.json](.gitbook/assets/openapi.json)
{% endswagger %}

{% swagger src=".gitbook/assets/openapi.json" path="/user/{username}" method="get" %}
[openapi.json](.gitbook/assets/openapi.json)
{% endswagger %}

{% swagger src=".gitbook/assets/openapi.json" path="/user/{username}" method="put" %}
[openapi.json](.gitbook/assets/openapi.json)
{% endswagger %}

{% swagger src=".gitbook/assets/openapi.json" path="/user/{username}" method="delete" %}
[openapi.json](.gitbook/assets/openapi.json)
{% endswagger %}
