<div style="font-weight: 200">

# Kun-Chieh (KC) Hsu <span style="vertical-align: middle;">[![](./assets/github.png)](https://github.com/sieginglion/resume)</span> <span style="vertical-align: middle;">[![](./assets/linkedin.png)](https://www.linkedin.com/in/sieginglion/)</span>

<div style="display: flex; justify-content: space-between; align-items: center;">
<div>

## Experience

- 9/14 National **Tsing Hua** University: materials science major, CS minor
- 7/17 ~ 8/19 (2.2Y) HIGH5.ai: **Full Stack Developer** \
  HIGH5 provided CRM solutions, including chatbots, web push notifications, and customer journey mapping, to brands and marketing companies. Our platform was capable of handling over 20,000 messages per hour. \
  Skills: **Python**, **NLP**, **Angular**, **Node.js**, **GCP**, **Elasticsearch**, **RabbitMQ**, **Docker**, **BitBucket Pipelines**, **Kubernetes**
- 6/20 ~ 6/23 (3Y) aetherAI: **Sr. DevOps** (the only)

</div>
<img src="./assets/sieginglion.jpeg" height=200></img>
</div>

## Tasks and Skills Used at aetherAI

\*The product was an AI pathology system, so all production deployments, except for Kubernetes image pulling, were conducted **offline**.

- **Environment Parity**: Designed a unified toolset for developers to bring up their own development environments independently and for field application engineers (FAEs) to deploy various production environments effortlessly. It had to be compatible with both **Docker Compose** and **Helm**, presenting a huge challenge in **configuration management**.

- **Kubernetes**: Successfully migrated the product from **Docker** to Kubernetes by incorporating a range of open-source solutions into it. These included **Helm**, **MicroK8s**, **Longhorn** (distributed block storage), **MetalLB** (bare metal load-balancer), **Patroni** (**high-availability PostgreSQL**), **SMB** driver, **Elastic stack**. Was responsible for team training afterwards.

- **CI/CD**: Responsible for optimizing all **Dockerfile**s, **GitLab CI** pipelines, managing **on-premises GitLab Runner**s and **container registry** (**Harbor**). Incorporated **Earthly** and **ArgoCD** into it. Designed a pipeline for packaging unique offline deployables for each customer, using ClickUp as the single source of truth.

- Monitoring: Designed an end-to-end monitoring solution for hospitals that only allowed **SMTP** outflow. This included a sidecar container built upon **Docker SDK** and **Kubernetes API** to send out the metrics as emails periodically. An internal CI pipeline processed and stored the data in **Elasticsearch**. Data visualization was done in **Grafana**, while **ElastAlert** handled Slack alerting. **Sentry** was used for on-site monitoring.

- Backend Development: Designed a network topology suitable for single-node, dual-node, and Kubernetes architectures, which was also secure during cross-node communication. Heavily relied on **Nginx**, **Caddy**, **mTLS**. Developed a fixed-rate load testing tool with **Golang**.

- **Windows Server**: Designed a **high-availability** and secure solution for a Windows Python server with **Powershell**, **Nginx**, **Caddy**, **mTLS**. Developed **Ansible Playbook**s for FAEs to install, update, and control it from Linux.

## Hobby Projects

### [stock-sense.info](https://stock-sense.info/)

A website features animated income statements and P/E ratio bands for public companies in the US and Taiwan. \
Skills: **Python**, **Plotly**, **Plotly Dash**, **Pandas**, **SEC API**, **Docker**, **GitHub Actions**, **Azure Container Apps**, **Namecheap**, **CloudFlare**

### [portman](https://github.com/sieginglion/portman)

My own portfolio management server which is capable of fetching historical prices for US and Taiwan stocks, as well as cryptocurrencies. Based on that, it can calculate downside risk for each position and conduct MACD parameter optimization. The trading signals are presented through a Streamlit app. \
Skills: **Numba**, **Python**, **FastAPI**, **NumPy**, **Streamlit**

### [ipttrace](https://pypi.org/project/ipttrace/)

A CLI let you trace iptables rules at ease \
Skills: **Python**, **typer**, **iptables**, **dmesg**, **PyPI**

### [kwarg-sort](https://marketplace.visualstudio.com/items?itemName=sieginglion.kwarg-sort)

A VS Code extension that sorts the keyword arguments in a Python function alphabetically. \
Skills: **JavaScript**, **VS Code API**

### [UltraTracer](https://github.com/sieginglion/UltraTracer)

Fast and Concise Ray Tracer with SIMD Acceleration \
Skills: **C++**

</div>
