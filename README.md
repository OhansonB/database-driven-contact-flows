Database-driven contact flows are contact flows in which the customer’s experience and other call routing factors are determined by values stored within a database - in this case DynamoDB - rather than ‘hard coded’ into the contact flow itself. 

When a caller routes through your Amazon Connect contact flow(s), a Lambda function is invoked to look-up and return data stored in DynamoDB based on the telephone number dialled or some other attribute; this data is set as contact attributes and referred to via the Check Contact Attribute block throughout your Contact Flows to determine the caller’s experience within the IVR.

The resources in this repository are associated with Substack article _Amazon Connect: Database-driven Contact Flows_
