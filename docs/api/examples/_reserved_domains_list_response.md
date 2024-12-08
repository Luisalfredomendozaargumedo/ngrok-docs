<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2024-12-08T10:05:52Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.4jfhbnmbgy4vtwmjc.local-ngrok-cname.com",
			"created_at": "2024-12-08T10:05:52Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2pvhFWE606FjNDTtwL2OamwNjS3",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2pvhFWE606FjNDTtwL2OamwNjS3"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2pvhFT9mEb0yftsSuwWYqSvtDMB",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2pvhFT9mEb0yftsSuwWYqSvtDMB"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.4jfhbnmbgy4vtwmjc.local-ngrok-cname.com",
			"created_at": "2024-12-08T10:05:52Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2pvhFR0Slzw8BjssbhKAZC5GoPp",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2pvhFR0Slzw8BjssbhKAZC5GoPp"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
