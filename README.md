<h2> 📖 About Me </h2>



<ul>
  <li>
    <p style="font-family:Arial; font-size:1.5em;">Improving myself on <b>AWS</b>, <b>Golang</b>, <b>Kubernetes</b>, <b>Cloud Native Technologies</b> and <b>Observability</b> Stack. </p>
  </li>
 </ul>

 <h2>📫 How to reach me:</h2>

[![Follow on Twitter](https://img.shields.io/badge/--twitter?label=Twitter&logo=Twitter&style=social)](https://twitter.com/uzumlukek_mk)
[![Connect on LinkedIn](https://img.shields.io/badge/--linkedin?label=LinkedIn&logo=LinkedIn&style=social)](https://www.linkedin.com/in/muhammedsaidkaya/)


<div style="width: 100vw; display:flex;">
  <div style="width: 40%;margin-left: 8em;">
    <h1> 👨🏽‍💻 WORK EXPERIENCE</h1>
    <h2><b>DevOps Engineer - Picus Security</b></h2>
    <h3>07/2022 - Present&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;San Francisco, California</h3>
      <li>
        <b>INFRASTRUCTURE - Provisioning and Maintaining Onprem Model(Kubernetes Cluster)</b>
        <ol>
        <li>
        Provisioning <b>K3S Kubernetes Cluster</b> and deploying applications/Postgre/Redis etc. with the <b>GitOps Flux CD Kustomization Controller.</b>
        </li>
        <li>
        Using <b>Mozilla SOPS</b> for Secret Management
        </li>
        <li>
        <b>Graceful Shutdown</b> for Postgre DB for avoiding Write-Ahead-Logging errors.
        </li>
        <li>
        Monitoring Cluster with Loki & Prometheus & Grafana (HELM)
        </li>
        <li>
        <b>Nginx Ingress Controller</b> and <b>Cert-Manager/TLS Certificates</b> (Custom/Default TLS & Lets Encrypt, etc...) <b>(Flux Conditional Bootstrapping & Variable Substitution)</b>
        </li>
        <li>
        Creating a <b>Mutating Admission Controller Webhook</b> for License Management (Patching)
        </li>
        <li>
         Pod-level Proxy/SSL Inspection Configuration for Flux
        </li>
        <li>
         Mirroring AWS S3 Bucket Objects with Minio Server/Gateway
        </li>  
        </ol>
      </li>
      <li>
        <b>INFRASTRUCTURE - Provisioning and maintaning SAAS (AWS)</b>
        <ol>
        <li> 
        <b>Terraform:</b> Route53 (Hostedzones), WAF (IPSets, Rules, Resource Association), ALB (Listeners and Target Group Rules), ECS ( EC2 Launch Type / ASG / Launch Template for User-data ), RDS ( Aurora ), Elasticache, SNS + SQS for Event Architecture, Kinesis Data Firehose for delivering WAF and APP logs, Opensearch for collecting APP logs, S3 for storing Configuration Files
        </li>
        <li>
        <b>AWS CDK with Python:</b> Cloudwatch Alarms
        </li>
        <li>
        <b>Serverless - Lambda:</b> Monitoring ECS/RDS Events and etc., Creating Opsgenie Alarms and Sending Slack Notifications
        </li>
        </ol>
      </li>
      <li>
        <b>PLATFORM - Setup Zero Trust OpenVPN Platform</b>
        <ol>
        <li>
        OpenVPN Community Server on AWS EC2
        </li>
        <li>
        Integrated Google 2FA Authenticator
        </li>
        <li>
        Slack Bot commands for VPN user management
        </li>
        </ol> 
      </li>
      <li>
        <b>AUTOMATION/TESTING - Setup E2E Test Infrastructure for Continuous Integration</b>
        <ol>
        <li>
        Creating Github Self-hosted Runner for Using Docker Cache Layers
        </li>
        <li>
        Docker Compose (Apps+DB+Redis+Nginx) with isolated Project/Network
        </li>
        <li>
        Paralel Cypress Execution by Test Tag
        </li>
        </ol>
      </li>
      <li>
        <b>AUTOMATION/PLATFORM - Setup Onprem Stable Release Approvement Mechanism for Continuous Delivery</b>
        <ol>
        <li>
        Creating K3s Kubernetes Cluster. Provisioning APPs with FluxCD.
        </li>
        <li>
        Slack Bot Commands for Release Management
        </li>
        </ol>
      </li>
      <li>
        <b>OBSERVABILITY - Setup Filebeat Log Agent Custom Processor</b>
        <ol>
        <li>
        Filebeat Custom Processors for injecting APP Git Commit SHA in order to keep track of number of panic errors which is related to specific commit
        </li>
        </ol>
      </li>
      <br/>
    </ul>
    <h2><b>Platform Engineer - kloia</b></h2>
    <h3>08/2021 - 07/2022&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;London - UK</h3>
    <h4 style="color: gray" ;>
      <i
        >kloia is a new-era consultancy company who is an accelerator for closing the technology gap through the adoption of modern practices in Cloud, DevOps, Test Automation and Microservices.</i
      >
    </h4>
    <ul style="list-style-type:none;">
      <li>
        Worked on the integration project of <b>Jenkins Shared Library</b> written in Groovy for the CI / CD implementation of Adaptive Branching, one of the branching methods.
      </li>
      <li>
        Worked on the project of creating <b>Upstream and Downstream Kubernetes Clusters</b> and their integrated components in the private cloud as code.
      </li>
      <li>
        Participated in the project of creating <b>a Monitoring Platform (Nginx, Prometheus, Grafana, Alertmanager)</b> using Ansible and <b>Custom Prometheus Exporter</b> using Python.
      </li>
      <li>
        Worked with APM(Instana) and <b>Opensource observability technologies (Opentelemetry/Opentracing etc.)</b> and how to get telemetry data in distributed architecture by manual/auto instrumentation.
      </li>
      <br/>
    </ul>
    <h2><b>Software Developer - Tübitak Bilgem YTE</b></h2>
    <h3>10/2020 - 08/2021&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;Ankara - Turkey</h3>
    <h4 style="color: gray" ;>
      <i
        >Tübitak Bilgem YTE develops R&D-oriented software solutions in order
to meet the digital transformation needs of public institutions.</i
      >
    </h4>
    <ul style="list-style-type:none;">
      <li>
        Involved in <b>"BKMYBS"</b> project which enables the joint management of the accounting transactions of all public institutions and organizations within the scope of the central government budget.
      </li>
      <li>
        <b>TECHNOLOGY STACK:</b> Ember.js, Spring Boot, Hibernate, PostgreSQL, Apache Kafka, ELK Stack and SOAP Web services.
      </li>
    </ul>
  </div>

  <div style="margin-left: 7vw;">
    <h2>💻 Tech Stack</h2>
    <table>
      <tr>
        <td>Core Technologies</td>
        <td>
          <img
            src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg"
            alt="git"
            width="70"
            height="70"
          /><img
            src="https://github.com/github/explore/raw/main/topics/linux/linux.png"
            alt="linux"
            width="70"
            height="70"
          /><img
            src="https://www.vectorlogo.zone/logos/nginx/nginx-ar21.svg"
            alt="nginx"
            width="70"
            height="70"
          /><img
            src="https://github.com/github/explore/raw/main/topics/bash/bash.png"
            alt="bash"
            width="70"
            height="70"
          />
        </td>
      </tr>
      <tr>
        <td>Cloud Provider</td>
        <td>
          <img
            src="https://www.vectorlogo.zone/logos/amazon_aws/amazon_aws-ar21.svg"
            alt="aws"
            width="70"
            height="70"
          />
        </td>
      </tr>
      <tr>
        <td>Serverless</td>
        <td>
          <img
            src="https://www.vectorlogo.zone/logos/serverless/serverless-ar21.svg"
            alt="serverless"
            width="70"
            height="70"
          /><img
            src="https://www.vectorlogo.zone/logos/amazon_awslambda/amazon_awslambda-ar21.svg"
            alt="lambda"
            width="70"
            height="70"
          />
        </td>
      </tr>
      <tr>
        <td>Cloud Native Technologies</td>
        <td>
          <img
            src="https://github.com/github/explore/raw/main/topics/docker/docker.png"
            alt="docker"
            width="70"
            height="70"
          /><img
            src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg"
            alt="kubernetes"
            width="70"
            height="70"
          /><img
            src="https://www.vectorlogo.zone/logos/rancher/rancher-ar21.svg"
            alt="k3s"
            width="70"
            height="70"
          /><img
            src="https://cncf-branding.netlify.app/img/projects/k3s/icon/color/k3s-icon-color.png"
            alt="rancher"
            width="70"
            height="70"
          /><img
            src="https://www.vectorlogo.zone/logos/fluxcdio/fluxcdio-ar21.svg"
            alt="flux"
            width="70"
            height="70"
          /><img
            src="https://cncf-branding.netlify.app/img/projects/helm/icon/color/helm-icon-color.png"
            alt="k3s"
            width="70"
            height="70"
          />
        </td>
      </tr>
      <tr>
        <td>Infrastructure as Code Tools</td>
        <td>
            <img
            src="https://www.vectorlogo.zone/logos/terraformio/terraformio-ar21.svg"
            alt="terraform"
            width="70"
            height="70"
            /><img
            src="https://github.com/github/explore/raw/main/topics/ansible/ansible.png"
            alt="ansible"
            width="70"
            height="70"
            />
        </td>
      </tr>
      <tr>
        <td>Observability & Monitoring</td>
        <td>
            <img
            src="https://raw.githubusercontent.com/cncf/artwork/master/projects/opentelemetry/stacked/color/opentelemetry-stacked-color.svg"
            alt="opentelemetry"
            width="70"
            height="70"
            /><img
            src="https://www.vectorlogo.zone/logos/jaegertracingio/jaegertracingio-ar21.svg"
            alt="jaeger"
            width="70"
            height="70"
            /><img
            src="https://www.vectorlogo.zone/logos/prometheusio/prometheusio-ar21.svg"
            alt="prometheus"
            width="70"
            height="70"
            /><img
            src="https://www.vectorlogo.zone/logos/grafana/grafana-ar21.svg"
            alt="grafana"
            width="70"
            height="70"
            /><img
            src="https://www.vectorlogo.zone/logos/fluentd/fluentd-ar21.svg"
            alt="fluentd"
            width="70"
            height="70"
            /><img
            src="https://www.vectorlogo.zone/logos/elastic/elastic-ar21.svg"
            alt="elastic"
            width="70"
            height="70"
            /><img
            src="https://www.vectorlogo.zone/logos/elasticco_kibana/elasticco_kibana-ar21.svg"
            alt="kibana"
            width="70"
            height="70"
            />
        </td>
      </tr>
      <tr>
        <td>CI/CD</td>
        <td>
            <img
        src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg"
        alt="jenkins"
        width="70"
        height="70"
        /><img
        src="https://www.vectorlogo.zone/logos/groovy-lang/groovy-lang-ar21.svg"
        alt="groovy"
        width="70"
        height="70"
        /><img
        src="https://www.vectorlogo.zone/logos/gitlab/gitlab-ar21.svg"
        alt="gitlab"
        width="70"
        height="70"
        /><img
        src="https://raw.githubusercontent.com/cncf/landscape/master/hosted_logos/github-actions.svg"
        alt="github-actions"
        width="70"
        height="70"
        />
        </td>
      </tr>
      <tr>
        <td>PL/Library & Frameworks</td>
        <td>
            <img
        src="https://www.vectorlogo.zone/logos/python/python-ar21.svg"
        alt="python"
        width="70"
        height="70"
        />
        <img
        src="https://github.com/github/explore/raw/main/topics/go/go.png"
        alt="go"
        width="70"
        height="70"
        /><img
        src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original-wordmark.svg"
        alt="java"
        width="70"
        height="70"
        /><img
        src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg"
        alt="spring"
        width="70"
        height="70"
        /><img
        src="https://www.vectorlogo.zone/logos/reactjs/reactjs-ar21.svg"
        alt="react"
        width="70"
        height="70"
        />
        </td>
      </tr>
      <tr>
        <td>Databases</td>
        <td>
            <img
            src="https://www.vectorlogo.zone/logos/postgresql/postgresql-ar21.svg"
            alt="postgresql"
            width="70"
            height="70"
            /><img
            src="https://www.vectorlogo.zone/logos/mysql/mysql-ar21.svg"
            alt="mysql"
            width="70"
            height="70"
            />
        </td>
      </tr>
      </table>
  </div>
</div>



<h2 align="left"> <a href="https://www.credly.com/users/muhammed-said-kaya/badges" style="text-decoration:none;color:black">🎖 Certificates</a></h2>
<p align="left">
<img src="assets/certificates/cka.png" alt="cka" width="170" height="170"/> 
<img src="assets/certificates/AWS-CP.png" alt="aws" width="170" height="170"/> 
<img src="assets/certificates/terraform-associate.png" alt="terraform" width="170" height="170"/>
<img src="assets/certificates/Terraform-CHIP.png" alt="terraform-chip" width="170" height="170"/>
</p>


<h2 align="left"> <a href="https://medium.com/@muhammedsaidkaya" style="text-decoration:none;color:black" >🖌 Latest Blog Post</a></h2>

<!-- BLOG-POST-LIST:START -->
- [Providing Least Privilege Access for AWS Aurora Postgres Database with ChatOps](https://medium.com/picus-security-engineering/providing-least-privilege-access-for-aws-aurora-postgres-database-with-chatops-83a5f99ee824?source=rss-bb6d038e35e3------2)
- [Pod-level Proxy Configuration on Kubernetes and Flux](https://medium.com/picus-security-engineering/pod-level-proxy-configuration-on-kubernetes-and-flux-47f258decda?source=rss-bb6d038e35e3------2)
- [On-premises S3 Bucket Object Storage with Minio Server/Gateway](https://medium.com/picus-security-engineering/on-premises-s3-bucket-object-storage-with-minio-server-gateway-4c44fc321b1c?source=rss-bb6d038e35e3------2)
- [OpenVPN Community Server with 2FA Google Authenticator on AWS EC2](https://medium.com/picus-security-engineering/openvpn-community-server-with-2fa-google-authenticator-on-aws-ec2-275f2e0722a6?source=rss-bb6d038e35e3------2)
- [Testing Production-Ready Applications on the Local Kubernetes Environment](https://medium.com/@muhammedsaidkaya/testing-of-production-ready-applications-on-the-local-kubernetes-environment-b1b0efc67b95?source=rss-bb6d038e35e3------2)
<!-- BLOG-POST-LIST:END -->


