# Network and Virtualization/production

## Learning Goals
  * Understand and use properties in the HTTP protocol (like Headers, caching,
    sessions and cookies)
  * Understand the same-origin policy related to REST and how to solve problems
    using CORS
  * Understand the concept Virtualization 
  * Understand and use x-as-a-service platforms
  * Understand and use concepts required to setup a Server with a domain name,
    Reverse Proxy and TLS 
  * Understand, conceptually, the workings of asymmetric encryption, signatures
    and certificates, with respect to TLS

## Business competences
This week will provide students with:
  * Knowledge of the http protocol, including relevant practical aspects such as
    setting up HTTPS, reverse-proxying, and CORS.

## Plan (starting from Tuesday)

### [Day 1](Day1) HTTP
Headers, Caching, HTTP Sessions and how they are implemented, cookies, and CORS

- [HTTP](http://www.tutorialspoint.com/http/http_tutorial.pdf)  
  This seems long, but has relatively few words per page. Read:
    * Chapters: 1,3-6  
    * Chapter 7 and 8 are good look-up resources for status codes and headers
      respectively. It will benefit you to just read the 1/2 page introductions
      to each of them, and then know that you can use them as references as
      needed in the future.
* [More comlete list of HTTP headers](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers)
- [Cookies](https://en.wikipedia.org/wiki/HTTP_cookie)  
  introduction and sections 2-5.
- [Same Origine Policy](https://en.wikipedia.org/wiki/Same-origin_policy)  
  introduction and sections: 1-4.
- [CORS](https://en.wikipedia.org/wiki/Cross-origin_resource_sharing)  
  introduction and sections 1-4.
- [slides](Day1/HTTP.pdf)

Additions after the lecture:
* [More comlete list of HTTP headers](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers)  
  This list of headers is both more extensive and easier to read than the
  chapter in the http\_tutorial.pdf
<!--
- [Slides](https://efif.sharepoint.com/sites/cph/Lyngby/_layouts/15/guestaccess.aspx?docid=05f956c9304fe4b3b9ef5e626ce1df3bd&authkey=AfFUG-AXhD79TJgI9sDhnxY)
  introduction and sections 1-4.
  -->

### [Day 2](Day2) HTTP continued
HTTPS, nginx, TLS, Cryptography, DNS.
- [Reverse Proxy (Nginx)](https://www.nginx.com/resources/glossary/reverse-proxy-server/)
- [Reverse Proxy](https://en.wikipedia.org/wiki/Reverse_proxy)
- [slides https](Day2/NetworkSecurity.pdf)
- [slides dns](Day2/dns.pdf)

### Day 3 Virtualisation and architecture
Virtualisation, architecture, x-as-a-service, tomcat.

- [Infrastructure as a Service](https://www.ibm.com/developerworks/cloud/library/cl-cloudservices1iaas/index.html)
- [Platform as a Service](https://www.ibm.com/developerworks/cloud/library/cl-cloudservices2paas/index.html)
- [slides](Day3/virtualization.pdf)

### Day 4 SP-exercise / Digital Ocean setup
TLS and HTTPS. How to set up DO with a domanin name, Nginx and TLS


## Exercises 

This week, everything is considered green.

  * [Day-1](https://docs.google.com/document/d/1OjKW7PGWn231x4mWqhDNtBqTfZGlrS7a21io--BnGLA/edit?usp=sharing) HTTP
  * [Setup your Droplet (and leave it running until after the exam) as explained here](https://docs.google.com/document/d/1dhdOmyrq2JQc-MxIgn-IsSq3if1crjPbgeFLy7vmWcw/edit)
  * [Day-4](https://docs.google.com/document/d/1BcewzHwKs7K0yOex1iWIbF27C9CdU8IdnNzZwHjgwJA/edit?usp=sharing) CORS

