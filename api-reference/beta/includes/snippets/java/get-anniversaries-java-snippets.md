---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

PersonAnniversaryCollectionPage anniversaries = graphClient.me().profile().anniversaries()
	.buildRequest()
	.get();

```