<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-12-08T10:06:19Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2pvhIvYRUHIUAwZ2oav8w5xuYhm",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2pvhIvYRUHIUAwZ2oav8w5xuYhm"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2pvhHT0VquwYNkiSZpt78ivXvuL",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2pvhHT0VquwYNkiSZpt78ivXvuL"
				},
				"enabled": true
			},
			"created_at": "2024-12-08T10:06:08Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2pvhHW0Ulmd7Ykqr5SldXb8ZjFd",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2pvhHW0Ulmd7Ykqr5SldXb8ZjFd"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
