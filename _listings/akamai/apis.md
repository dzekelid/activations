---
name: Akamai
x-slug: akamai
description: Akamai Technologies, Inc. is a content delivery network or CDN and cloud
  services provider headquartered in Cambridge, Massachusetts, in the United States.
  Akamais content delivery network is one of the worlds largest distributed computing
  platforms, responsible for serving between 15 and 30 percent of all web traffic.
  The company operates a network of servers around the world and rents capacity on
  these servers to customers who want their websites to work faster by distributing
  content from locations close to the user
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
x-kinRank: "9"
x-alexaRank: ""
tags: Activations
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/activations/master/_listings/akamai/apis.md
specificationVersion: "0.14"
apis:
- name: Akamai API List Current Cloudlets Origin Activations
  x-api-slug: akamai-api
  description: List Current Cloudlets Origin Activations
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/origins/currentActivations
  tags: Cloudlets, Origins, Activations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activations/master/_listings/akamai/cloudletsapiv2originscurrentactivations-get-openapi.md
- name: Akamai API List Activations for a Cloudlets Origin
  x-api-slug: akamai-api
  description: List Activations for a Cloudlets Origin
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/origins/{originId}/activations
  tags: Cloudlets, Origins, Activations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activations/master/_listings/akamai/cloudletsapiv2originsoriginidactivations-get-openapi.md
- name: Akamai API Activate a Cloudlets Origin Version
  x-api-slug: akamai-api
  description: Activate a Cloudlets Origin Version
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/origins/{originId}/activations
  tags: Cloudlets, Origins, Activations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activations/master/_listings/akamai/cloudletsapiv2originsoriginidactivations-post-openapi.md
- name: Akamai API List Policy Activations
  x-api-slug: akamai-api
  description: List Policy Activations
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/policies/{policyId}/activations
  tags: Cloudlets, Policies, Activations, Network,propertyname
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activations/master/_listings/akamai/cloudletsapiv2policiespolicyidactivations-get-openapi.md
- name: Akamai API Activate a Policy Version
  x-api-slug: akamai-api
  description: Activate a Policy Version
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/policies/{policyId}/versions/{version}/activations
  tags: Cloudlets, Policies, Versions, Activations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activations/master/_listings/akamai/cloudletsapiv2policiespolicyidversionsversionactivations-post-openapi.md
- name: Akamai API List a Property&#8217;s Activations
  x-api-slug: akamai-api
  description: List a Property&#8217;s Activations
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/properties/{propertyId}/activations/
  tags: Papi, V0, Properties, Property, Activations, Contract,group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activations/master/_listings/akamai/papiv0propertiespropertyidactivations-get-openapi.md
- name: Akamai API Create a New Activation
  x-api-slug: akamai-api
  description: Create a New Activation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///{&quot;type&quot;:&quot;/papi/v0/activation-warnings-not-acknowledged&quot;}
  tags: Activations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activations/master/_listings/akamai/quottypequotquotpapiv0activationwarningsnotacknowledgedquot-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activations/master/_listings/akamai/quottypequotquotpapiv0activationwarningsnotacknowledgedquot-post-openapi.md
- name: Akamai API
  x-api-slug: akamai-api
  description: Akamai Technologies, Inc. is a content delivery network or CDN and
    cloud services provider headquartered in Cambridge, Massachusetts, in the United
    States. Akamais content delivery network is one of the worlds largest distributed
    computing platforms, responsible for serving between 15 and 30 percent of all
    web traffic. The company operates a network of servers around the world and rents
    capacity on these servers to customers who want their websites to work faster
    by distributing content from locations close to the user
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com//
  tags: Activations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activations/master/_listings/akamai/openapi.md
x-common:
- type: x-base
  url: https://api.ccu.akamai.com
- type: x-blog
  url: https://blogs.akamai.com
- type: x-blog-rss
  url: http://blogs.akamai.com/feeds.html
- type: x-crunchbase
  url: http://www.crunchbase.com/company/akamai-technologies
- type: x-developer
  url: https://developer.akamai.com/
- type: x-email
  url: open-developer@akamai.com
- type: x-github
  url: https://github.com/akamai
- type: x-twitter
  url: https://twitter.com/Akamai
- type: x-website
  url: https://akamai.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---