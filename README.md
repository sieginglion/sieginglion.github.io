<div style="font-weight: 300;">

# Kun-Chieh (KC) Hsu <span style="vertical-align: middle;">[![](./assets/github.png)](https://github.com/sieginglion/resume)</span> <span style="vertical-align: middle;">[![](./assets/linkedin.png)](https://www.linkedin.com/in/sieginglion/)</span>

<div style="display: flex; justify-content: space-between; align-items: center;">
<div>

## Experience

- 9/14 National **Tsing Hua** University: materials science major, CS minor
- 7/17 ~ 8/19 (2.2Y) HIGH5.ai: **ML and Full Stack Developer** (founding team) \
  HIGH5 provided CRM solutions for brands and marketing companies, including chatbots, web push notifications, and customer journey mapping. I developed a system that enabled customers to train their own sentence classification models on request. Later, I took on the responsibility of maintaining both the frontend and backend codebases. \
  Stack: **NumPy**, **scikit-learn**, **PyTorch**, **NLP**, **NetworkX**, **Angular**, **Node.js**, **Elasticsearch**, **RabbitMQ**, **Docker**, **BitBucket Pipelines**, **Kubernetes**, **GCP**
- 6/20 ~ 6/23 (3Y) aetherAI: **Sr. DevOps** (the only)

</div>
<img src="./assets/sieginglion.jpeg" height=200></img>
</div>

## Hobby Projects

### [stock-sense.info](https://stock-sense.info/)

A website visualizes historical income statements of public companies as animated Sankey diagrams.
Stack: **Pandas**, **Plotly**, **Plotly Dash**, **SEC API**, **Docker**, **GitHub Actions**, **Azure Container Apps**, **Namecheap**, **CloudFlare**

### [portman](https://github.com/sieginglion/portman)

My own portfolio management server which is capable of fetching and calculating dividend-adjusted historical prices for both US and Taiwanese stocks, as well as cryptos. With the data, the statistical downside risk of each position can be calculated and the MACD parameters can be optimized. The trading signals are visualized through a Streamlit app. \
Stack: **NumPy**, **Numba**, **FastAPI**, **Streamlit**, **Plotly**

### [ipttrace](https://pypi.org/project/ipttrace/)

A CLI let you trace iptables rules at ease \
Stack: **Python**, **typer**, **iptables**, **dmesg**, **PyPI**

### [kwarg-sort](https://marketplace.visualstudio.com/items?itemName=sieginglion.kwarg-sort)

A VS Code extension that sorts the keyword arguments of a Python function alphabetically. \
Stack: **JavaScript**, **VS Code API**

### [UltraTracer](https://github.com/sieginglion/UltraTracer)

Concise ray tracer with SIMD acceleration \
Stack: **C++**

## Tasks and Stack Used at aetherAI

\*The product was an AI pathology system, so all production deployments, except for Kubernetes image pulling, were conducted **offline**.

- **Environment Parity**: Designed a unified toolset for developers to bring up their own development environments independently and for field application engineers (FAEs) to deploy various production environments effortlessly. It had to be compatible with both **Docker Compose** and **Helm**, presenting a huge challenge in **configuration management**.

- **Kubernetes**: Successfully migrated the product from **Docker** to Kubernetes by incorporating a range of open-source solutions into it. These included **Helm**, **MicroK8s**, **Longhorn** (distributed block storage), **MetalLB** (bare metal load-balancer), **Patroni** (**high-availability PostgreSQL**), **SMB** driver, **Elastic stack**. Was responsible for team training afterwards.

- **CI/CD**: Responsible for optimizing all **Dockerfile**s, **GitLab CI** pipelines, managing **on-premises GitLab Runner**s and **container registry** (**Harbor**). Incorporated **Earthly** and **ArgoCD** into it. Designed a pipeline for packaging unique offline deployables for each customer, using ClickUp as the single source of truth.

- Monitoring: Designed an end-to-end monitoring solution for hospitals that only allowed **SMTP** outflow. This included a sidecar container built upon **Docker SDK** and **Kubernetes API** to send out the metrics as emails periodically. An internal CI pipeline processed and stored the data in **Elasticsearch**. Data visualization was done in **Grafana**, while **ElastAlert** handled Slack alerting. **Sentry** was used for on-site monitoring.

- Backend Development: Designed a network topology suitable for single-node, dual-node, and Kubernetes architectures, which was also secure during cross-node communication. Heavily relied on **Nginx**, **Caddy**, **mTLS**. Developed a fixed-rate load testing tool with **Golang**.

- **Windows Server**: Designed a **high-availability** and secure solution for a Windows Python server with **Powershell**, **Nginx**, **Caddy**, **mTLS**. Developed **Ansible Playbook**s for FAEs to install, update, and control it from Linux.

</div>
