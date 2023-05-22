
> Services need to run on all interfaces (like 0.0.0.0) and not just localhost.
<br>
> Services need to be accessible via HTTP and **not** HTTPS.

Run Nginx on port 80 using Docker:

```
docker run -p 80:80 nginx:alpine
```{{exec}}

Now access Nginx using this link:

[ACCESS NGINX]({{TRAFFIC_HOST1_80}})

It's also possible to access ports using the top-right navigation in the terminal.
Or we can display the link to that page:

[ACCESS PORTS]({{TRAFFIC_SELECTOR}})



> Services need to run on all interfaces (like 0.0.0.0) and not just localhost.
<br>
> Services need to be accessible via HTTP and **not** HTTPS.

Expose Apache on port 1234 using Docker:

```
docker run -p 1234:80 httpd:alpine
```{{exec}}

Now access Apache using this link:

[ACCESS APACHE]({{TRAFFIC_HOST1_1234}})

It's also possible to access ports using the top-right navigation in the terminal.
Or we can display the link to that page:

[ACCESS PORTS]({{TRAFFIC_SELECTOR}})