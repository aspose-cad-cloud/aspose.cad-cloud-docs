---
title: "JPEG2000 API"
type: docs
url: /working-with-aspose-cad-cloud-formats-api/jpeg2000/
weight: 40
---

# **Introduction**
This article explains how to work with the JPEG2000 API. Using the following APIs, you can work with an image in the storage and process new ones:

1. [PUT /cad/{name}/jpeg2000](https://reference.aspose.cloud/cad/#!/Jpeg2000/PutDrawingJpeg2000)
1. [POST /cad/jpeg2000](https://reference.aspose.cloud/cad/#!/Jpeg2000/PostDrawingJpeg2000)

## **Resource URI**
[Swagger UI](https://reference.aspose.cloud/cad/) lets you call Aspose.CAD REST APIs directly from the browser.

## **cURL Example**
**Export drawing to JPEG2000 format**

{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

// First get Access Token
// Get App Key and App SID from https://dashboard.aspose.cloud/

 curl -v "https://api.aspose.cloud/connect/token" \
 -X POST \
 -d 'grant_type=client_credentials&client_id=xxxx&client_secret=xxxx' \
 -H "Content-Type: application/x-www-form-urlencoded" \
 -H "Accept: application/json"



// cURL example to export Drawing to JPEG2000 format

curl -v "https://api.aspose.cloud/v3.0/cad/jpeg2000" \
-X PUT \
-H "Content-Type: multipart/form-data" \
-H "Accept: application/json" \
-H "Authorization: Bearer <jwt token>" \
-F "drawingData=file.dxf" \
-o result.jpeg2000

// cURL example to export an existing drawing to JPEG2000 format with export settings specified

curl -v "https://api.aspose.cloud/v3.0/cad/jpeg2000" \
-X POST \
-H "Content-Type: application/json" \
-H "Accept: application/json" \
-H "Authorization: Bearer <jwt token>" \
-d "options=JPEG2000 options passed as a JSON" \
-o result.jpeg2000

Export an existing drawing to
```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

JPEG2000 file 

```

{{< /tab >}}

{{< /tabs >}}
            
# **SDKs**
Using an SDK (API client) is the quickest way for a developer to speed up the development. An SDK takes care of a lot of low-level details of making requests and handling responses and lets you focus on writing code specific to your particular project. Checkout our [GitHub repository](https://github.com/aspose-cad-cloud) for a complete list of Aspose.CAD SDKs along with working examples, to get you started in no time. Please check [Available SDKs](/cad/available-sdks/) article to learn how to add an SDK to your project.
## **SDK Examples**
**Export drawing to JPEG2000 format.**
{{< tabs tabTotal="2" tabID="2" tabName1="C#" tabName2="Python">}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cad-gists" "08d6d4c55fe96b77e1e9c57a2f36d6ba" "Example-cad-cloud-net-put-jpeg2000.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cad-gists" "7fd0ee4ef54697f442abdcbb41abbe10" "Example-cad-cloud-python-put-jpeg2000.py" >}}

{{< /tab >}}
{{< /tabs >}}


**Export an existing drawing to JPEG2000 format with export settings specified.**
{{< tabs tabTotal="2" tabID="3" tabName1="C#" tabName2="Python">}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cad-gists" "08d6d4c55fe96b77e1e9c57a2f36d6ba" "Example-cad-cloud-net-post-jpeg2000.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cad-gists" "7fd0ee4ef54697f442abdcbb41abbe10" "Example-cad-cloud-python-post-jpeg2000.py" >}}

{{< /tab >}}
{{< /tabs >}}
