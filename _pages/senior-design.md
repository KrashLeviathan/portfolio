---
layout:    page
permalink: "/senior-design"
author:    nkarasch
keywords:  Software Engineering senior design project capstone SE494 SE491 SE492 ISU iastate
title:     Hammer-io
menutitle: Senior Design
weight:    80
excerpt:   This page contains information about the author's senior design project.
--- 

![hammer-io logo]({{ "/assets/Viking_Hammer_Logo_1.png" | absolute_url }}){:style="display:block;width:150px;margin:0 auto;"}

<h1 style="text-align:center;">A DevOps framework offering an opinionated approach to developing and managing microservice applications in Node.js.</h1>

- - -

## Problem

There is a tendency to develop software as a collection of managed microservices.
The microservice architecture involves a fair amount of complexity that may
intimidate small teams with limited resources, limited time, or limited domain
knowledge. Often the microservices need to be deployed to the cloud. As a result,
another constraint on a small team is maintaining the system as its various
components are updated independently of each other. Traditionally this is
managed by a separate “DevOps” team; however, again, a small team with limited
resources may not be able to dedicate people to the task. These two primary
concerns—the overhead involved in setting up a microservices architecture and
the resources involved in maintaining one—outline the main problem this project
is addressing: that a microservices architecture may not be feasible for small
teams, such as students or startups.

## Solution

We will create a framework for developing Javascript-based microservices that
exhibit specific quality attributes, as well as provide an automated DevOps
process for managing the development and deployment of these JavaScript
microservices. The project will be built in Node.js, an open-source server
framework for running JavaScript code.

![hammer-io logo]({{ "/assets/hammer-io-pillars.png" | absolute_url }}){:style="display:block;width:100%;margin:0 auto;"}

## Purpose

By creating a framework for Node.js microservices, teams with limited
knowledge, resources, and time can quickly get started with a simple
infrastructure. We also provide the tools and structure to monitor and
maintain the health of their applications in development and in production.
This lets more developers start making cool things faster.

## Goals

The main goal of our project is to create an environment to develop
JavaScript microservices as well as a DevOps process to manage and monitor
its deployment.

Specifically, we hope to create an app that requires minimal configuration
and setup. This means the user would download one or two different tools
and then have scripts create most of the configuration files needed with
account info (e.g. GitHub, Docker Hub, etc.) supplied by the developers.
Easy-to-use CLI/GUI tools would be available to push, deploy, and create
new microservices.

Another goal that fits into this process is creating a seamless deployment
workflow. This looks like a user pushing code to a master branch and
watching his or her changes reflected in the live product a short while
later. Once the application is deployed, the user then tracks the status
of the application through a Data Monitoring app, which can notify
interested parties when a service goes offline, display metrics related to
server performance, etc. In addition, the Data Monitoring tool should be
able to perform load balancing between microservices.

## More Information

Please visit the [Hammer-io website](https://hammer-io.github.io/){:target="_blank"} to see
all documents pertaining to the project. The code can be found in the open-source
[hammer-io GitHub repository](https://github.com/hammer-io/){:target="_blank"}.
