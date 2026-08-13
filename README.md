# Auth Repeater

A Burp Suite extension that repeats the same HTTP request using different user credentials and compares the responses.

## Features

* Multiple user profiles.
* Supports `Cookie`, `Authorization`, and custom headers.
* Automatically repeats requests for each user.
* Logs:

  * HTTP method
  * URL
  * Status code
  * Response length
  * Response time
* Request and Response viewer for each result.

## Usage

1. Load the `.jar` in **Burp Suite → Extensions**.
2. Open the **Auth Repeater** tab.
3. Configure the scope and headers for each user.
4. Save the environment.
5. Right-click a request.
6. Select **Send to Auth Repeater**.
7. Review the results and select a row to inspect the Request and Response.

## Purpose

Helps identify authorization issues by comparing the behavior of the same endpoint across different users and privilege levels.

> Use only on systems you own or have permission to test.


![a](/imagen1.png)

![b](/imagen2.png)
