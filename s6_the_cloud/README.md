# Cloud computing

[Slides](../slides/Cloud%20Intro.pdf){ .md-button }

<p align="center">
  <img src="../figures/icons/engine.png" width="130">
  <img src="../figures/icons/bucket.png" width="130">
  <img src="../figures/icons/build.png" width="130">
  <img src="../figures/icons/registry.png" width="130">
  <img src="../figures/icons/vertex.png" width="130">
</p>

Running computations locally is often sufficient when only playing around with code in initial phase of
development. However, to really scale your experiments you will need more computing power than what your
standard laptop/desktop can offer. You probably already have experience with running on a local cluster
or similar but todays topic is about utilizing cloud computing.

<!-- markdownlint-disable -->
<figure markdown>
![Image](../figures/cloud_computing.jpeg){ width="600" }
<figcaption>
<a href="https://towardsdatascience.com/how-to-start-a-data-science-project-using-google-cloud-platform-6618b7c6edd2"> Image credit </a>
</figcaption>
</figure>
<!-- markdownlint-restore -->

There exist a [numerous](https://github.com/zszazi/Deep-learning-in-cloud) amount of cloud compute providers
with some of the biggest being:

* Azure
* AWS
* Google Cloud project
* Alibaba cloud

The all have slight advantages and disadvantages over each others. In this course we are going to focus on
Google cloud, because they have been kindly enough to sponsor $50 of cloud credit to each student. If you
happen to run out of credit, you can also get some free credit for a limited amount of time when you
signup with a new account. What's important to note is that all these different cloud providers all have the same set of
services, and that learning how to use the services of one cloud provider in many cases translate to also know how to
use the same services at another cloud provider. The services are called something different and can have a bit of
a different interface/interaction pattern but in the end it does not really matter.

Todays exercises are about getting to know how to work with the cloud. If you are in doubt about anything or want to
deep dive into some topics, I can recommend watching this
[series of videos](https://www.youtube.com/watch?v=4D3X6Xl5c_Y&list=PLIivdWyY5sqKh1gDR0WpP9iIOY00IE0xL)
or going through the [general docs](https://cloud.google.com/docs).

!!! tip "Learning objectives"

    The learning objectives of this session are:

    * In general being familiar with the Google SDK working
    * Being able to start different compute instances and work with them
    * Know how to setup continues integration workflows for building of docker images
    * Knowledge about how to store data and containers/artifacts in cloud buckets
    * Being able to train simple deep learning models using a combination of services
