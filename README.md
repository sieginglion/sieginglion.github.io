<div style="display: flex; align-items: center;">
    <div style="margin-right: 10px; font-size: 20px">Kun-Chieh (KC) Hsu</div>
    <div>
        <a href="https://github.com/sieginglion/">
            <img src="assets/github.png" style="margin-right: 5px;"/>
        </a>
        <a href="https://www.linkedin.com/in/sieginglion/">
            <img src="assets/linkedin.png"/>
        </a>
    </div>
</div>

Experience
14/9 National Tsing Hua University: Major in Materials Science, minor in CS
17/7 ~ 19/9 (2.25Y) HIGH5.ai: Full Stack Developer
20/6 ~ 23/6 (3Y) aetherAI: Sr. DevOps (the only)

What did I do in my last job?
\*All production deployments (except k8s image pulling) were done offline.

Environment Parity: Create a unified process for developers to bring up their own dev envs and for field application engineers (FAEs) to deploy different prod envs. Should be compatible with both Docker Compose and Helm.

Kubernetes: Help the company migrate from docker to k8s. Incorporate various open sourced solutions to the product: Helm, MicroK8s, Longhorn, MetalLB, Patroni (Zalando’s cloud native Postgres), SMB driver, Elastic stack.

CI/CD: Maintain all the Dockerfiles. Introduce Earthly. Maintain all the GitLab CI pipelines, on-premises GitLab Runner, on-premises container registry (Harbor). Introduce ArgoCD for staging env.

Monitoring: All outflow traffic except SMTP is blocked in hospitals. Responsible for designing a sidecar container utilizing Docker SDK, Kubernetes API to collect the metrics which will later be sent out as mails. In-house CI will then retrieve it, parse it, dump into Elasticsearch then for Grafana displaying. ElastAlert for slack alerting. Also use Sentry for in-hospital monitoring.

Network Topology: Maintain and design the network topology across single/dual-node, K8s version. Design how cross node communication is authed and encrypted (mTLS) and a procedure for FAEs to install the CA effortlessly.

Windows Server: Make a python server HA and secure on windows (PowerShell, Caddy, mTLS) and package them into an offline package so FAEs can deploy it from Linux, utilizing ansible-playbook under the hood
