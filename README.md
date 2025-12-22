# Hi there 👋 I'm Sushin K 

I'm a **Cloud Security Software Engineer** with over 7 years of experience building secure, scalable cloud-native systems. Based in Bengaluru, I specialize in securing Kubernetes clusters, container runtimes, service meshes, and cloud infrastructure through code. I focus on security-first design for distributed systems, building tools that harden cloud workloads, and automating security controls at scale across AWS, GCP, and on-premise data centers.

## 🔭 I'm currently working on:

**❤️ Rust 🦀 + Go for cloud security tooling**  

- **Cloud-native security automation** at Lumen Technologies: Building Kubernetes admission controllers, OPA policies, and security operators using Go/Rust
- **Container runtime security**: Developing eBPF-based runtime security monitors and syscall filtering for containerd/CRI-O
- **Infrastructure security**: Hardening service mesh configurations (Istio/Linkerd), implementing mTLS at scale, and automating zero-trust network policies
- **Personal projects**: 
  - Kubernetes security scanner (Rust + kube-rs)
  - Cloud workload identity and SPIFFE/SPIRE integrations
  - Infrastructure-as-code security scanner for Terraform/Pulumi
  - eBPF-based DDoS mitigation for cloud workloads

## 🌱 I'm currently learning:

- **CNCF security ecosystem**: Falco, Tetragon, Cilium, OPA/Gatekeeper, cert-manager, Sigstore
- **eBPF for cloud security**: Building runtime security tools with Aya (Rust) and libbpf-rs
- **Zero-trust architectures**: SPIFFE/SPIRE, Istio ambient mesh, BeyondCorp patterns
- **Supply chain security**: In-toto, SLSA, image signing with Cosign/Sigstore
- **Advanced Kubernetes security**: Pod Security Standards, seccomp/AppArmor profiles, admission control
- **Cloud-native threat detection**: Building detection rules for Falco, integrating with SIEM/SOAR

## 🚀 I'm looking to collaborate on:

- **CNCF security projects**: Contributing to Falco, Cilium, OPA, Tetragon, or similar runtime/network security tools
- **Open-source Kubernetes security**: Admission controllers, security operators, policy engines
- **Cloud security automation**: Infrastructure scanning, compliance-as-code, security posture management
- **eBPF security tooling**: Runtime security, network policy enforcement, observability

## 🤔 I'm looking for help with:

- Scaling eBPF-based security solutions across heterogeneous Kubernetes clusters (kernel version compatibility)
- Optimizing Rust async runtime performance for high-throughput security event processing (Tokio vs async-std tradeoffs)

## 💬 Ask me about:

- **Kubernetes security**: Hardening clusters, Pod Security Standards, admission control, RBAC design, secrets management (Vault, External Secrets Operator)
- **Container security**: Image scanning (Trivy, Grype), runtime protection, seccomp/AppArmor, rootless containers
- **Service mesh security**: Istio/Linkerd configuration, mTLS automation, authorization policies
- **Cloud infrastructure security**: AWS Security Hub, GCP Security Command Center, IAM policy automation
- **IaC security**: Terraform/Pulumi best practices, policy-as-code with OPA/Sentinel
- **Network security in cloud**: Calico, Cilium, network policies, microsegmentation

## 📫 How to reach me:

- GitHub: [sushink70](https://github.com/sushink70)
- Email: sushink70@gmail.com | sushink70@protonmail.com
- LinkedIn: [sushink70](https://linkedin.com/in/sushink70)
- Website: https://sushink70.github.io/sushink70/

## 😄 Pronouns: He/Him

## ⚡ Fun fact: 
I've automated security compliance across 1000+ cloud workloads and reduced container vulnerability remediation time by 75% through CI/CD pipeline integration!

## 🛠️ Cloud Security Tech Stack

**Core Languages**: Rust, Go, Python, C++, Bash  
**Orchestration/Control Plane**: TypeScript, Python

### Cloud Native & Kubernetes
- **Platforms**: Kubernetes, OpenShift, EKS, GKE, AKS
- **Container Runtimes**: containerd, CRI-O, Docker
- **Service Mesh**: Istio, Linkerd, Cilium
- **Policy & Admission**: OPA/Gatekeeper, Kyverno, Falco
- **Observability**: Prometheus, Grafana, Jaeger, OpenTelemetry
- **Secret Management**: HashiCorp Vault, External Secrets Operator, Sealed Secrets

### Security & Compliance
- **Runtime Security**: Falco, Tetragon, Tracee, Sysdig
- **Network Security**: Cilium, Calico, Network Policies
- **Image Security**: Trivy, Grype, Clair, Harbor
- **Supply Chain**: Cosign, Sigstore, in-toto, SLSA
- **eBPF Tools**: Aya (Rust), libbpf, bpftrace
- **Policy as Code**: OPA (Rego), Cedar, Kyverno policies
- **Security Testing**: OWASP ZAP, Nuclei, Burp Suite, Metasploit

### Cloud Platforms & Infrastructure
- **Cloud Providers**: AWS (EKS, GuardDuty, Security Hub, IAM, KMS), GCP (GKE, Security Command Center, Workload Identity)
- **IaC**: Terraform, Pulumi, Crossplane, Helm
- **CI/CD**: GitHub Actions, GitLab CI, ArgoCD, Flux
- **Identity**: SPIFFE/SPIRE, OAuth2/OIDC, Workload Identity

### Systems & Low-Level
- **Languages**: Rust (kube-rs, tokio, aya), Go (client-go, operator-sdk), C++
- **Datastores**: PostgreSQL, ScyllaDB, etcd, Redis
- **Sandboxing**: gVisor, Kata Containers, Firecracker

## 🚀 Key Cloud Security Projects

### Production Systems (Lumen Technologies)
**Cloud DDoS Mitigation Platform**: Built Kubernetes-native DDoS detection and mitigation using Cilium eBPF, with automated BGP flowspec injection. Reduced mitigation time from 15min to <30s.

**Kubernetes Security Posture Scanner**: Developed Go-based operator that continuously audits cluster security (PSS violations, RBAC misconfigurations, exposed services). Integrated with Falco for runtime correlation.

**Multi-Cloud Secret Rotation Pipeline**: Automated secret rotation across AWS/GCP using External Secrets Operator + Vault, with zero-downtime rollout via progressive delivery (Argo Rollouts).

### Open Source Contributions
- **Falco Rules**: Custom rulesets for detecting cloud-native attacks (container escapes, privilege escalation, crypto mining)
- **kube-rs**: Contributed admission webhook framework and controller examples
- **Cilium**: Network policy testing and documentation improvements

### Personal Projects
**k8s-security-scanner** (Rust + kube-rs): Admission controller that validates security contexts, secrets exposure, and image provenance using Sigstore verification.

**ebpf-runtime-guardian** (Rust + aya): eBPF-based syscall filter that blocks suspicious container behavior (network to sensitive ports, filesystem writes outside allowlist).

**iac-policy-engine** (Go + OPA): Terraform/Pulumi scanner that enforces security policies pre-deployment (exposed S3 buckets, overprivileged IAM, unencrypted resources).

**spiffe-workload-attestor** (Rust): Lightweight SPIFFE workload attestor for non-Kubernetes environments with hardware-backed attestation (TPM).

## 🎓 Education & Certifications

- **B.E. in Electronics and Communication Engineering** – Anna University, Chennai (2016)
- **Certified Kubernetes Security Specialist (CKS)** – CNCF 
- **Certified Kubernetes Administrator (CKA)** – CNCF 
- **Certified Ethical Hacker v11 (CEH)** – EC-Council (2021-2022)
- **AWS Certified Security – Specialty** – Amazon 
- **Google Professional Cloud Security Engineer** – Google Cloud
- **CCNA/CCNP Security** – Networkers Home (2019)

## 🏆 Career Achievements

- Reduced Kubernetes security incidents by 80% through automated admission control and runtime monitoring
- Implemented zero-trust networking across 500+ microservices using Istio + SPIFFE
- Built security automation that cut cloud compliance audit time from weeks to hours
- Promoted to P3 at Lumen Technologies for cloud security platform contributions
- Achieved 99.9% uptime for DDoS mitigation services protecting 1000+ customer networks

## 🌟 Core Focus Areas

- **Cloud-native security**: Kubernetes, containers, service mesh hardening
- **Runtime security**: eBPF-based detection, syscall filtering, anomaly detection
- **Zero-trust architecture**: Workload identity, mTLS automation, policy enforcement
- **Supply chain security**: Image signing, SBOM generation, provenance verification
- **Security automation**: Policy-as-code, compliance-as-code, infrastructure hardening

## 📚 CNCF Projects I Work With

**Security**: Falco, OPA, Notary, TUF, in-toto, SPIFFE/SPIRE  
**Networking**: Cilium, Calico, Istio, Linkerd, Envoy  
**Runtime**: containerd, CRI-O, gVisor, Kata Containers  
**Observability**: Prometheus, Jaeger, OpenTelemetry, Fluentd  
**Orchestration**: Kubernetes, Helm, Argo (CD/Rollouts/Events)

---

Check out my GitHub for cloud security tools and CNCF contributions!

## ⚠️ Important Notice  

I create cloud security software strictly for **defensive and ethical purposes**.  
By using any of my code, you agree to the following:  

- ❌ You must not use my work for illegal, harmful, or unethical activities  
- ❌ My code is prohibited from use in:  
  - Offensive security operations without proper authorization  
  - Systems that violate privacy or data protection laws  
  - Financial exploitation or gambling platforms  
  - NSFW or adult content infrastructure  
  - Any project that causes harm to individuals or organizations  

✅ My intention is to strengthen cloud infrastructure security, promote secure-by-default practices, and contribute to the CNCF ecosystem.  

I am **not responsible** for any misuse, damages, or consequences caused by those who ignore these terms. Use responsibly.
