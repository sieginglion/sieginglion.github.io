<div style="font-weight: 200">

# Kun-Chieh (KC) Hsu <span style="vertical-align: middle;">[![](assets/github.png)](https://github.com/sieginglion/)</span> <span style="vertical-align: middle;">[![](assets/linkedin.png)](https://www.linkedin.com/in/sieginglion/)</span>

## Experience

- 9/14 National **Tsing Hua** University: materials science major, CS minor
- 7/17 ~ 8/19 (2.2Y) HIGH5.ai: **Full Stack**
- 6/20 ~ 6/23 (3Y) aetherAI: **Sr. DevOps** (the only)

## Tasks and Skills in aetherAI

\*All prod deployments (except k8s image pulling) were done **offline**.

- **Environment Parity**: Design a unified process for developers to bring up their own dev envs independently and for field application engineers (FAEs) to deploy varios prod envs efficiently. It's compatible with both **Docker Compose** and **Helm**.

- **Kubernetes**: Migrate the major product from **Docker** to K8s. Incorporate a range of open-source solutions into it, including **Helm**, **MicroK8s**, **Longhorn** (distributed block storage), **MetalLB**, **Patroni** (**high-availability PostgreSQL**), **SMB** driver, **Elastic stack**.

- **CI/CD**: Maintain all **Dockerfile**s, **GitLab CI** pipelines, **on-premises GitLab Runner**, **on-premises container registry** (**Harbor**). Incorporate **Earthly** and **ArgoCD** into it.

- Monitoring: Responsible for designing an e2e monitoring solution for hospitals that only allow **SMTP** outflow. It involves a sidecar container built upon **Docker SDK** and **Kubernetes API** for data collection, with metrics sent by email. An internal CI pipeline will process and store this data in **Elasticsearch**. Data visualization will be done in **Grafana**, while **ElastAlert** will handle Slack notifications. **Sentry** will be used for on-site monitoring.

- Network Topology: Design a network topology suitable for single-node, dual-node, and Kubernetes architectures. which is also secure during cross node communication.Heavily rely on **Nginx**, **Caddy**, **mTLS**.

- **Windows Server**: Design a **high-availability** and secure solution for a Windows Python server with **Powershell**, **Nginx**, **Caddy**, **mTLS**. Develop **Ansible Playbook**s for FAEs to install/update/control it from Linux. Develop a CI that packages them into a single offline deployable.

## Hobby Projects

### https://stock-sense.info/

A website show income statements of US/TW public companies as animations. Also include corresponding P/E Ratio \
Skills: **Python**, **Plotly**, **Plotly Dash**, **Pandas**, **SEC API**, **Docker**, **GitHub Actions**, **Azure Container Apps**, **Namecheap**, **CloudFlare**

### portman

My own investment portfolio management server that fetches historical prices for U.S. and Taiwan stocks, dividend-adjusted, and includes cryptocurrency data. It evaluates portfolio positions based on downside risk and optimizes MACD parameters to generate trading signals, all visualized through a Streamlit app. stock-sense.info depends on it. \
Skills: **Numba**, **Python**, **FastAPI**, **NumPy**, **streamlit**

### [ipttrace](https://pypi.org/project/ipttrace/)

A CLI let you trace iptables rules at ease, skills: **Python**, **typer**, **iptables**, **dmesg**, **PyPI**

### [kwarg-sort](https://marketplace.visualstudio.com/items?itemName=sieginglion.kwarg-sort)

If you are also an obsessive-compulsive disorder patient like me, here's a VS Code extension that help you sort Python function kwargs alphabetically \
skills: **JavaScript**, **VS Code API**

### UltraTracer

Fast and Concise Ray Tracer with SIMD Acceleration

Skills: **C++**

</div>
