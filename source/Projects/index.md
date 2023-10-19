---
title: Projects
date: 2023-10-14 00:45:26
academia: true
---

<style>
    .projects-table {
        width: 100%;
        border-collapse: collapse;
        margin: 0 auto;
    }
    .projects-table td {
        border: 0;
        text-align: center;
        vertical-align: middle;
    }
    .projects-table img {
        max-width: 200px;
        height: auto;
        margin-right: 20px;
    }
     .projects-table .paper p {
        text-align: left;
        margin: 0;
    }
</style>

<table class="projects-table">
    <tr>
        <td><img src="/img/ablator.png" alt="Abaltor"></td>
        <td class="paper">
                  <br>
                  <papertitle>ABLATOR: Robust Horizontal-Scaling of Machine Learning Ablation Experiments</papertitle><br>
                  <em>AutoML</em>, 2023
                  <br>
                  <a href="https://github.com/fostiropoulos/ablator">project page</a>
                  /
                  <a href="./data/ablator.pdf">paper</a>
                  <p></p>
                  <p>
                    Ablation experiments are important in improving Machine Learning (ML) models, where multiple
                    experimental trials are required for each component of a ML model. We find lack of available tools
                    and frameworks for horizontal scaling of ML experiments where manual effort is required that often
                    lead to errors. We propose a statefull experiment design framework, ABLATOR, that can scale a single
                    experiment to thousands of trials while being fault-tollerant and robust to errors. We performed the
                    largest ablation experiment for tabular data on Transformer models to date, evaluating 2,337 models
                    in total. Finally, we open source ABLATOR;
                  </p>
                  <br>
                </td>
    </tr>
    <tr>
        <td><img src="/img/ablator.png" alt="Abaltor"></td>
        <td class="paper">
                  <br>
                  <papertitle>RocketMqOperator: Auto Mangane RocketMq Cluster Instance on an Cloud Platform</papertitle>
                  <br>
                  <a href="https://github.com/apache/rocketmq-operator" style="color:blue;">project page</a>
                  <p></p>
                  <p>
                    The RocketMQ Operator automatically deploys and manages RocketMQ clusters on the Kubernetes-based cloud environment. RocketMQ is a popular distributed messaging and streaming platform with low latency, high performance and reliability, trillion-level capacity, and flexible scalability.
                  </p>
                  <p>· Horizontal Scaling - Safely and seamlessly scale up each component of RocketMQ.
                  </p>
                  <p>· Rolling Update - Gracefully perform rolling updates in order with no downtime.
                  </p>
                  <p>· Multi-cluster Support - Users can deploy and manage multiple RocketMQ name server clusters and broker clusters on a single Kubernetes cluster using RocketMQ Operator.
                  </p>
                  <p>· Topic Transfer - Operator can automatically migrate a specific topic from a source broker cluster to a target cluster without affecting the business.
                  </p>
                  <br>
                </td>
    </tr>
</table>
