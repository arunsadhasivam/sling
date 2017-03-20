http://localhost:8080/content/product.json
http://localhost:8080/content/product.xml
http://localhost:8080/content/product.html


FLOW:
======
http://localhost:8080/content/product.html  -- >should access product/catalog  --> product/catalog of /apps.

<jcr:root xmlns:sling="http://sling.apache.org/jcr/sling/1.0" xmlns:jcr="http://www.jcp.org/jcr/1.0"
    jcr:primaryType="nt:unstructured"
    jcr:title="Product catalog"
    jcr:description="This is a product availability page node"
    sling:resourceType="product/catalog"/>
