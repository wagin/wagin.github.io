---
layout: default
title: Raghavendra Challapali - Principal Engineer & Manager
---

# Raghavendra Challapali
## Principal Engineer & Manager

**Contact Information:**  
Phone: +91-8892847134  
Email: challapali@gmail.com  
GitHub: [https://github.com/wagin](https://github.com/wagin)  
LinkedIn: [Raghavendra Challapali](https://www.linkedin.com/in/raghavendra-challapali)

## Education
**Indian Institute of Technology, Madras**  
CSE, B.Tech & M.Tech (Dual Degree), 2013

## Objective
Engineering Manager with 12+ years of overall experience driving software architecture, design, and backend development, combined with
over 3+ years of proven success in engineering management. Skilled in building and leading highly functional engineering teams, scaling large
systems, and aligning technical strategies with business goals to solve complex enterprise problems.

## Skills

### Languages
Python, Golang, NodeJS, Bash, Perl, C++

### SQL/NoSQL Databases
PostgreSQL, Redis, Cassandra, Prometheus, InfluxDB, Clickhouse, TimeScaleDB, OpenTSDB

### Web/Backend Frameworks
Django, Supabase, FlutterFlow, Celery, Tornado, RabbitMQ, Kafka, OpenTelemetery, Nginx, Gunicorn, Flask, HashiCorp Vault, Tastypie, Django Rest Framework, Jinja2, OpenSSL.

### Development Tools/Environments
Kubernetes, Docker, AWS+ Boto3, GIT, Ansible, Vagrant, Terraform, OpenTofu, VMWare, VirtualBox, Kibana, HashiCorp Consul, Fabric, SendGrid API

## Work Experience

### PRINCIPAL ENGINEER & MANAGER
**Rafay Systems - Bangalore, KA**  
*December 2021 - Present*

As the Engineering Manager for the Data Services Platform at Rafay, I am responsible for the FinOps and monitoring dashboards, System Alerts, and Events.

- Hiring and managing a sleek, efficient team of six engineers, including Backend, UI, QA, and DevOps engineers, to design, develop, and scale the Data Services Platform to meet Customers’ expectations.
- Interact regularly with the Enterprise Leadership, Product, and Solutions Teams to understand and break down customer requirements into Engineering Tasks.
- Over 3.5 Years, I have efficiently facilitated the timely delivery of numerous products from the ground up:
  o Billing System for Rafay’s PaaS offering is used by GPU providers, and it integrates with 3rd-party ERP solutions.
  o FinOps product to optimize the cost of applications running in Kubernetes based on usage patterns.
  o Event-based Dashboards backed by an OLAP database, Clickhouse, to monitor any environment, such as VMs, BareMetal, Databases, Load Balancers, etc.
  o Cost Management for Kubernetes resources deployed in AKS, EKS, Bare Metal, and VMs.
- Scaling the metrics platform by evaluating TSDBs (InfluxDB, OpenTSDB, Prometheus) and implementing tenant-based sharding.
- Contribution to open-source projects like OpenCost, influxdb-relay, & Paralus for improvements or fix issues.

#### Portfolio
<div style="display: flex; overflow-x: auto; gap: 16px; padding-bottom: 10px; width: 800px;">
  <div style="min-width: 280px; width: 800px; flex-shrink: 0;">
    <a href="https://rafay.co/cloud-cost-optimization" target="_blank" rel="noopener noreferrer"><p>Cloud Cost Management and Optimization</p></a>
    <div class="carousel" style="position: relative; overflow: hidden; width: 100%; height: 100%;">
      <div class="slides" style="display: flex; transition: transform 0.5s ease;">
        <img src="/assets/images/cost-management.jpg" alt="Cloud Cost Management and Optimization" style="width: 100%; height: auto;">
      </div>
      <button onclick="prevSlide(this)" style="position: absolute; left: 5px; top: 40%; background: rgba(0,0,0,0.5); color: white;">❮</button>
      <button onclick="nextSlide(this)" style="position: absolute; right: 5px; top: 40%; background: rgba(0,0,0,0.5); color: white;">❯</button>
    </div>
  </div>
  <div style="min-width: 280px; width: 800px; flex-shrink: 0;">
    <a href="https://rafay.co/gpu-paas/" target="_blank" rel="noopener noreferrer" style="display: block; text-align: center; margin-top: 5px;"><p style="text-align: center;">GPU PaaS<sup>TM</sup> Billing</p></a>
    <div class="carousel" style="position: relative; overflow: hidden; width: 100%; height: 100%;">
      <div class="slides" style="display: flex; transition: transform 0.5s ease;">
        <img src="/assets/images/gpu-paas.jpg" alt="GPU PaaS<sup>TM</sup>" style="width: 100%; flex-shrink: 0;">
        <img src="/assets/images/paas-billing.jpg" alt="PaaS Billing and Chargeback" style="width: 100%; flex-shrink: 0;">
      </div>
      <button onclick="prevSlide(this)" style="position: absolute; left: 5px; top: 40%; background: rgba(0,0,0,0.5); color: white;">❮</button>
      <button onclick="nextSlide(this)" style="position: absolute; right: 5px; top: 40%; background: rgba(0,0,0,0.5); color: white;">❯</button>
    </div>
  </div>
</div>

<script>
function nextSlide(btn) {
  const slides = btn.parentElement.querySelector('.slides');
  const total = slides.children.length;
  const current = parseInt(slides.getAttribute('data-index') || 0);
  const next = (current + 1) % total;
  slides.style.transform = `translateX(-${next * 100}%)`;
  slides.setAttribute('data-index', next);
}

function prevSlide(btn) {
  const slides = btn.parentElement.querySelector('.slides');
  const total = slides.children.length;
  const current = parseInt(slides.getAttribute('data-index') || 0);
  const prev = (current - 1 + total) % total;
  slides.style.transform = `translateX(-${prev * 100}%)`;
  slides.setAttribute('data-index', prev);
}
</script>


### Technical Advisor
**Archonet - Bangalore, KA**  
*August 2021 – April 2023*

Archonet is a new gen Digital Platform for Architects and Interior Designers. As a Technical Advisor, set up their technology infrastructure:

- Creating Docker based Infrastructure (EC2 Instances, DNS, Load Balancers, VPCs, CloudFront, etc) on AWS
- Setting up all required development, CICD, collaboration and monitoring tools like GitHub, GitHub Actions, Slack, Google Workspace, Google Analytics, Database Admin tools, Webhook Servers, etc
- Hiring and managing UI/UX freelancers to design and develop Archonet's Beta launch product
- Training the founders on FlutterFlow and Supabase to help them create the App with No Code Platform

### Senior Lead Software Engineer
**Akamai Technologies India Pvt. Ltd. - Bangalore, KA**  
*July 2016 – November 2021*

Worked as Lead Developer for Zero Trust at Akamai, involved in design, development and scaling of a multi-tenant system to maintain tenant-based configuration and tenant's user validation, authorization and authentication.

- **Directory Sync System:** Initialized with product, scale and security requirements; designed an architecture for Integrating Enterprise Users via AD, LDAP and SCIM into Akamai's Enterprise Products. Successfully led the product into production by defining SDLC and coding standards; on-boarding SDEs and SDETs with effective resource planning; and handling integrations across teams
- **Architecture Scaling and HA:** Revisited all the state-based components integral to Zero Trust architecture to evaluate its capacity and redesigned it to handle a scale of 100s of tenants with millions of users each
- **Upgrade Portal:** Designed and architected a product for upgrading a network of servers playing various roles. The Upgrade Portal was a POC for handling system upgrades at a scale of 100s of instances seamlessly with click of a button
- Developed various features integral to Zero Trust for customer acquisitions – Integration of Cisco Duo for MFA, Enabling Active Directory password to change remotely, Categorization of Applications, Customized multi-language support for user portal
- Soha Systems: Joined as a Senior Backend Engineer and had a successful exit via acquisition by Akamai

### Software Engineer
**Compile India Pvt. Ltd. - Bangalore, KA**  
*February 2013 – June 2016*

As a part of core engineering team at Compile was involved in developing intelligent sales product (Compile Sales) and a marketing insights product (Compile IS).

- Designed, developed and deployed a full-scale product for generating marketing insights using job postings and news articles
- Designed and developed an NLP system for crawling, extracting text, classifying and processing large scale of documents (PDFs) for identifying buying intent of technology products like Storage, Security, Networking and CRM products
