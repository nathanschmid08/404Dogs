# 404 Dogs

| Code | Name                           | Description |
|------|--------------------------------|-------------|
| **1xx Informational** | | |
| 100  | Continue                       | Client should continue with request |
| 101  | Switching Protocols            | Server is switching protocols |
| 102  | Processing                     | Server is processing the request (WebDAV) |
| 103  | Early Hints                    | Hints for client (e.g. preload) |
| **2xx Success** | | |
| 200  | OK                             | Request succeeded |
| 201  | Created                        | Resource successfully created |
| 202  | Accepted                       | Request accepted, not yet processed |
| 203  | Non-Authoritative Information  | Response modified by a proxy |
| 204  | No Content                     | No response body |
| 205  | Reset Content                  | Client should reset form |
| 206  | Partial Content                | Partial response (range requests) |
| 207  | Multi-Status                   | Multiple statuses (WebDAV) |
| 208  | Already Reported               | Resource already reported (WebDAV) |
| 226  | IM Used                        | Response with delta encoding |
| **3xx Redirection** | | |
| 300  | Multiple Choices               | Multiple options available |
| 301  | Moved Permanently              | Resource permanently moved |
| 302  | Found                          | Temporary redirect |
| 303  | See Other                      | Retrieve resource from different URI |
| 304  | Not Modified                   | Resource not modified |
| 305  | Use Proxy                      | Must access via proxy (deprecated) |
| 306  | (Unused)                       | Reserved, no longer used |
| 307  | Temporary Redirect             | Temporary redirect, method unchanged |
| 308  | Permanent Redirect             | Permanent redirect, method unchanged |
| **4xx Client Error** | | |
| 400  | Bad Request                    | Invalid request syntax |
| 401  | Unauthorized                   | Authentication required |
| 402  | Payment Required               | Reserved for future use |
| 403  | Forbidden                      | Access denied |
| 404  | Not Found                      | Resource not found |
| 405  | Method Not Allowed             | Method not supported |
| 406  | Not Acceptable                 | Content not acceptable |
| 407  | Proxy Authentication Required  | Authentication with proxy required |
| 408  | Request Timeout                | Request took too long |
| 409  | Conflict                       | Conflict in request |
| 410  | Gone                           | Resource permanently removed |
| 411  | Length Required                | Content-Length header required |
| 412  | Precondition Failed            | Precondition not met |
| 413  | Payload Too Large              | Request body too large |
| 414  | URI Too Long                   | URI too long |
| 415  | Unsupported Media Type         | Media type not supported |
| 416  | Range Not Satisfiable          | Invalid range header |
| 417  | Expectation Failed             | Expectation not met |
| 418  | I’m a teapot                   | April Fools' joke (RFC 2324) |
| 421  | Misdirected Request            | Request sent to wrong server |
| 422  | Unprocessable Entity           | Semantic error (WebDAV) |
| 423  | Locked                         | Resource locked (WebDAV) |
| 424  | Failed Dependency              | Dependency failed (WebDAV) |
| 425  | Too Early                      | Request sent too early |
| 426  | Upgrade Required               | Client must upgrade protocol |
| 428  | Precondition Required          | Precondition required |
| 429  | Too Many Requests              | Rate limit exceeded |
| 431  | Request Header Fields Too Large| Request headers too large |
| 451  | Unavailable For Legal Reasons  | Blocked for legal reasons |
| **5xx Server Error** | | |
| 500  | Internal Server Error          | Generic server error |
| 501  | Not Implemented                | Method not implemented |
| 502  | Bad Gateway                    | Invalid response from upstream |
| 503  | Service Unavailable            | Server unavailable |
| 504  | Gateway Timeout                | Timeout from upstream server |
| 505  | HTTP Version Not Supported     | Unsupported HTTP version |
| 506  | Variant Also Negotiates        | Configuration error |
| 507  | Insufficient Storage           | Not enough storage (WebDAV) |
| 508  | Loop Detected                  | Infinite loop detected (WebDAV) |
| 510  | Not Extended                   | Further extensions required |
| 511  | Network Authentication Required| Network authentication required |
