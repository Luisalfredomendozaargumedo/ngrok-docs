<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2024-12-08T10:06:15Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2pvhIL9gcPCQBzdwOwHBa5JeSMy",
					"uri": "https://api.ngrok.com/event_destinations/ed_2pvhIL9gcPCQBzdwOwHBa5JeSMy"
				}
			],
			"id": "esb_2pvhIPoC6imbu4Pjq9tbEUYcpdo",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2pvhIPoC6imbu4Pjq9tbEUYcpdo/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2pvhIPoC6imbu4Pjq9tbEUYcpdo"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```
