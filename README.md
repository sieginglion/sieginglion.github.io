# Kun-Chieh (KC) Hsu <span style="vertical-align: middle;">[![](assets/github.png)](https://github.com/sieginglion/)</span> <span style="vertical-align: middle;">[![](assets/linkedin.png)](https://www.linkedin.com/in/sieginglion/)</span>

## Experience

- 9/14 National **Tsing Hua** University: materials science major, CS minor
- 7/17 ~ 8/19 (2.2Y) HIGH5.ai: **Full Stack**
- 6/20 ~ 6/23 (3Y) aetherAI: **Sr. DevOps** (the only)

## Tasks and Skills in aetherAI

\*All production deployments (except k8s image pulling) were done **offline**.

- Environment Parity: Create a unified process for developers to bring up their own dev envs and for field application engineers (FAEs) to deploy varios prod envs, compatible with both **Docker Compose** and **Helm**.

- Kubernetes: Help the company migrate from docker to k8s. Incorporate various open sourced solutions to the product: Helm, MicroK8s, Longhorn, MetalLB, Patroni (Zalando’s cloud native Postgres), SMB driver, Elastic stack.

- CI/CD: Maintain all the Dockerfiles. Introduce Earthly. Maintain all the GitLab CI pipelines, on-premises GitLab Runner, on-premises container registry (Harbor). Introduce ArgoCD for staging env.

- Monitoring: All outflow traffic except SMTP is blocked in hospitals. Responsible for designing a sidecar container utilizing Docker SDK, Kubernetes API to collect the metrics which will later be sent out as mails. In-house CI will then retrieve it, parse it, dump into Elasticsearch then for Grafana displaying. ElastAlert for slack alerting. Also use Sentry for in-hospital monitoring.

- Network Topology: Maintain and design the network topology across single/dual-node, K8s version. Design how cross node communication is authed and encrypted (mTLS) and a procedure for FAEs to install the CA effortlessly.

- Windows Server: Make a python server HA and secure on windows (PowerShell, Caddy, mTLS) and package them into an offline package so FAEs can deploy it from Linux, utilizing ansible-playbook under the hood

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
