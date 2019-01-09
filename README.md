# Cloud & DevOps Engineering - Technical test
We think infrastructure is best represented as code, and management of resources should be automated as much as possible.

Your task is to provision a simple 2-tier application architecture with a load balancer and an application server. You are free to use any provisioning tool and target of your choice. We tend to use Terraform and Azure.

We have included a dummy application server written in Go in this repository as `app.go`. This file has been precompiled as a release in `app-linux-x86-64` for your convenience.

* Your solution should install the attached application on 2 Linux servers. If you wish, you may use a configuration management tool
* Requests to the application should be load balanced between the 2 servers
* The public entry point to the application should be HTTP 80/TCP
* The application servers should be adequately secured

