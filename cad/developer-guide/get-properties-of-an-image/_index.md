---
title: "Get Properties of an Image"
type: docs
url: /get-properties-of-an-image/
weight: 10
---

# **Introduction**
This article explains how to get properties of an image. With following Aspose.CAD API you can get properties of an image:

- [GET /cad/{name}/properties](https://apireference.aspose.cloud/cad/#!/Properties/GetImageProperties)
## **Resource URI**
[Swagger UI](https://apireference.aspose.cloud/cad/) lets you call Aspose.CAD REST APIs directly from the browser. The description of the APIs and their parameters are also given there.
## **cURL Example**

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



// cURL example to get properties of an image

curl -v "https://api.aspose.cloud/v3.0/cad/910609.dxf/properties" \
-X GET \
-H "Content-Type: application/json" \
-H "Accept: application/json" \
-H "Authorization: Bearer <jwt token>"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "DefaultFont": null,

  "SpecifiedEncoding": "Default",

  "MaxPoint": "(308.64; 207.26; 0)",

  "MinPoint": "(109.39; 76.79; 0)",

  "AcadVersion": "AC1012",

  "Height": "130",

  "Width": "199",

  "Code": 200,

  "Status": "OK"

}

```

{{< /tab >}}

{{< /tabs >}}
# **SDKs**
Using an SDK (API client) is the quickest way for a developer to speed up the development. An SDK takes care of a lot of low-level details of making requests and handling responses and lets you focus on writing code specific to your particular project. Checkout our [GitHub repository](https://github.com/aspose-cad-cloud) for a complete list of Aspose.CAD SDKs along with working examples, to get you started in no time. Please check [Available SDKs](/cad/available-sdks/) article to learn how to add an SDK to your project.
## **SDK Examples**
{{< tabs tabTotal="5" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Ruby" tabName4="Python" tabName5="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cad-gists" "08d6d4c55fe96b77e1e9c57a2f36d6ba" "Examples-.NET-GetImageProperties.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "771038f7ed5885cfde27c52a9fa2de33" "Examples-CAD-PHP-Get-CAD-Properties.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "4622acaf999d638b0735551bd1aa2709" "Examples-CAD-PHP-Get-CAD-Properties.rb" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cad-gists" "7fd0ee4ef54697f442abdcbb41abbe10" "Get-CAD-Properties.py" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "49dc674a9de19e007289548bd69e1486" "Get-CAD-Properties.js" >}}

{{< /tab >}}

{{< /tabs >}}
