<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [HTTP Response Status Codes Summary](#http-response-status-codes-summary)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

### HTTP Response Status Codes Summary

HTTP response status codes indicate the outcome of a client's request. They are grouped into five categories:

1. **Informational Responses (100 – 199)**:
   - **100 Continue**: Client should continue with the request.
   - **101 Switching Protocols**: Server switches to a different protocol as requested.
   - **102 Processing (WebDAV)**: Request is being processed, but no response is yet available.
   - **103 Early Hints**: Allows client to start preloading resources while the server prepares the final response.

2. **Successful Responses (200 – 299)**:
   - **200 OK**: Request succeeded.
   - **201 Created**: New resource created as a result of the request.
   - **202 Accepted**: Request received but not yet acted upon.
   - **203 Non-Authoritative Information**: Returned metadata from a local or third-party copy.
   - **204 No Content**: No content to send, but headers may be useful.
   - **205 Reset Content**: Tells the client to reset the document view.
   - **206 Partial Content**: Partial content delivered as requested.
   - **207 Multi-Status (WebDAV)**: Information about multiple resources.
   - **208 Already Reported (WebDAV)**: Avoids repeating enumeration of internal members.
   - **226 IM Used**: Result of instance-manipulations applied to the resource.

3. **Redirection Messages (300 – 399)**:
   - **300 Multiple Choices**: Multiple possible responses.
   - **301 Moved Permanently**: Resource permanently moved to a new URL.
   - **302 Found**: Resource temporarily moved to a different URL.
   - **303 See Other**: Directs client to get resource from another URI with a GET request.
   - **304 Not Modified**: Response has not been modified; use cached version.
   - **305 Use Proxy (Deprecated)**: Access must be done through a proxy (deprecated).
   - **306 (Unused)**: Reserved and no longer used.
   - **307 Temporary Redirect**: Resource temporarily moved, use the same HTTP method.
   - **308 Permanent Redirect**: Resource permanently moved, use the same HTTP method.

4. **Client Error Responses (400 – 499)**:
   - **400 Bad Request**: Server cannot process the request due to client error.
   - **401 Unauthorized**: Authentication is required.
   - **402 Payment Required (Experimental)**: Reserved for future use.
   - **403 Forbidden**: Client does not have access rights.
   - **404 Not Found**: Requested resource not found.
   - **405 Method Not Allowed**: Request method not supported.
   - **406 Not Acceptable**: No content matching the criteria.
   - **407 Proxy Authentication Required**: Authentication with a proxy is needed.
   - **408 Request Timeout**: Server timed out waiting for the request.
   - **409 Conflict**: Request conflicts with server state.
   - **410 Gone**: Resource has been permanently deleted.
   - **411 Length Required**: Content-Length header field is required.
   - **412 Precondition Failed**: Server does not meet client's preconditions.
   - **413 Payload Too Large**: Request entity is too large.
   - **414 URI Too Long**: Requested URI is too long.
   - **415 Unsupported Media Type**: Media format is not supported.
   - **416 Range Not Satisfiable**: Range specified is not valid.
   - **417 Expectation Failed**: Server cannot meet the expectation.
   - **418 I'm a teapot**: Server refuses to brew coffee with a teapot.
   - **421 Misdirected Request**: Request was directed at the wrong server.
   - **422 Unprocessable Content (WebDAV)**: Request was well-formed but contained semantic errors.
   - **423 Locked (WebDAV)**: Resource is locked.
   - **424 Failed Dependency (WebDAV)**: Request failed due to a previous request failure.
   - **425 Too Early (Experimental)**: Server is unwilling to risk processing a possibly replayed request.
   - **426 Upgrade Required**: Client should switch to a different protocol.
   - **428 Precondition Required**: Request must be conditional to prevent conflicts.
   - **429 Too Many Requests**: Client has sent too many requests in a given time period.
   - **431 Request Header Fields Too Large**: Request headers are too large.
   - **451 Unavailable For Legal Reasons**: Resource is legally unavailable.

5. **Server Error Responses (500 – 599)**:
   - **500 Internal Server Error**: Server encountered an error.
   - **501 Not Implemented**: Request method is not supported.
   - **502 Bad Gateway**: Invalid response from an upstream server.
   - **503 Service Unavailable**: Server is temporarily unavailable.
   - **504 Gateway Timeout**: Upstream server failed to send a response in time.
   - **505 HTTP Version Not Supported**: HTTP version is not supported.
   - **506 Variant Also Negotiates**: Transparent content negotiation configuration error.
   - **507 Insufficient Storage (WebDAV)**: Server cannot store the representation needed.
   - **508 Loop Detected (WebDAV)**: Infinite loop detected while processing the request.
   - **510 Not Extended**: Further extensions are required for the request.
   - **511 Network Authentication Required**: Client needs to authenticate to gain network access.



