# WAPT Task 1: Web Fundamentals

**Author:** Raman Kumar
**Program:** IqraSec Academy, WAPT Internship, Phase 1
**Platform:** TryHackMe

## About this repository
This repository contains my work for Task 1 (Web Fundamentals) of the
Web Application Penetration Testing (WAPT) internship. The goal of this task
was to understand how web applications work before testing them for
vulnerabilities, because every web attack is built on HTTP requests and responses.

## Rooms completed
| # | Room | Link | Status |
|---|------|------|--------|
| 1 | Web Application Basics | https://tryhackme.com/room/webapplicationbasics | Completed |
| 2 | HTTP in Detail | https://tryhackme.com/room/httpindetail | Completed |

## Topics covered
- Client, web server and WAF roles
- URL structure (scheme, host, port, path, query string, fragment)
- HTTP and HTTPS
- Requests and responses
- HTTP methods: GET, POST, PUT, DELETE
- Headers (Host, User-Agent, Content-Type, Content-Length)
- Cookies and sessions (Set-Cookie)
- Status codes (2xx, 3xx, 4xx, 5xx)
- Security headers: CSP, HSTS, X-Content-Type-Options (nosniff)
- Basic API requests

## Practical work
- **Web Application Basics:** sent GET, POST and DELETE requests to an API
  (`/api/users`, `/api/user/1`) and saw how the same endpoint behaves
  with different methods.
- **HTTP in Detail:** made GET, DELETE, PUT and POST requests to a practice site
  (`/room`, `/blog?id=1`, `/user/1`, `/user/2`, `/login`) and matched
  methods and status codes to real situations.

## Tools used
- TryHackMe (rooms and built-in request tool)
- Browser and Developer Tools

## Key learnings
- Every web attack is a modified HTTP request, so I need to understand normal
  traffic first.
- The server must check authorisation for every method, not only GET.
- URL parameters and request bodies are user input and must never be trusted.
- Status codes and security headers give useful signals when testing.
- Cookies keep sessions alive, so Secure and HttpOnly flags matter.


