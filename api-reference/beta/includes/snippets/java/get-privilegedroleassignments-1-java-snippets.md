---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

IPrivilegedRoleAssignmentCollectionPage privilegedRoleAssignments = graphClient.privilegedRoleAssignments()
	.buildRequest()
	.get();

```