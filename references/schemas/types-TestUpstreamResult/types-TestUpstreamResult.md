# types.TestUpstreamResult

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `content` | string | No | Content is the extracted text content from the upstream response. |
| `error` | string | No | Error is the error message when the test fails (e.g. timeout, network error). |
| `ok` | boolean | No | OK indicates whether the upstream returned a 2xx status code. |
| `request` | string | No | Request is the masked request summary (url, method, headers, body). |
| `response_body` | string | No | ResponseBody is the raw response body from the upstream. |
| `status` | integer | No | Status is the HTTP status code returned by the upstream. |
| `status_text` | string | No | StatusText is the HTTP status text returned by the upstream. |

