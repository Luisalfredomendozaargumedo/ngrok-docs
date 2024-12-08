<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2024-12-08T10:06:11Z",
			"hostport": "e4ce6d835910.ngrok.paid:443",
			"id": "ep_2pvhHublEJUgsA4TGGE5mf57kOR",
			"name": "command_line",
			"principal": {
				"id": "usr_2pvhFKrTHEnN5j5fIS7gIREzxNF",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://e4ce6d835910.ngrok.paid",
			"tunnel": {
				"id": "tn_2pvhHublEJUgsA4TGGE5mf57kOR",
				"uri": "https://api.ngrok.com/tunnels/tn_2pvhHublEJUgsA4TGGE5mf57kOR"
			},
			"tunnel_session": {
				"id": "ts_2pvhHqFrKUyCwW7Y0upRYY653SP",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2pvhHqFrKUyCwW7Y0upRYY653SP"
			},
			"type": "ephemeral",
			"updated_at": "2024-12-08T10:06:11Z",
			"upstream_url": "http://localhost:80",
			"url": "https://e4ce6d835910.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2024-12-08T10:06:08Z",
			"domain": {
				"id": "rd_2pvhHUDILZODQnMqF2C3aHgDOry",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2pvhHUDILZODQnMqF2C3aHgDOry"
			},
			"edge": {
				"id": "edgtls_2pvhHW0Ulmd7Ykqr5SldXb8ZjFd",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2pvhHW0Ulmd7Ykqr5SldXb8ZjFd"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2pvhHSISekzgr3J4uxYbx0jI7eT",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2024-12-08T10:06:08Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
