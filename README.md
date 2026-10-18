
# AI Security Engineering 360°

**Cybersecurity Professional | AI Security | SOC | Detection Engineering | Red Teaming | GRC | DevSecOps**

Building practical expertise in cybersecurity, AI security, defensive engineering, offensive security, and secure AI systems through hands-on labs, research, and authorized security assessments.

AI Sentinel is my security engineering portfolio for exploring vulnerabilities, evaluating security controls, developing detections, and researching the security of AI-powered applications, large language models (LLMs), retrieval-augmented generation (RAG), autonomous agents, and Model Context Protocol (MCP) integrations.

> **Mission:** Understand how systems fail, reproduce security weaknesses in authorized environments, validate defenses, and turn findings into practical security improvements.

---

## 📌 Table of Contents

- [About Me](#-about-me)
- [Security Domains](#-security-domains)
- [Security Tooling and Platforms](#-security-tooling-and-platforms)
- [AI Security Tooling](#-ai-security-tooling)
- [LLM Guardrails Security](#-llm-guardrails-security)
- [AI Red Teaming](#-ai-red-teaming-and-adversarial-testing)
- [RAG Security](#-rag-security)
- [AI Agent Security](#-ai-agent-security)
- [MCP Security](#-mcp-security)
- [AI Supply-Chain and Model Security](#-ai-supply-chain-and-model-security)
- [AI Security Monitoring](#-ai-security-monitoring-and-ai-soc)
- [AI Engineering](#-ai--llm-engineering)
- [AI Governance and GRC](#-ai-governance-risk-and-compliance)
- [Hands-On Labs](#-hands-on-security-labs)
- [Learning Roadmap](#-learning-roadmap)
- [Responsible Testing](#-responsible-testing)
- [References](#-project-links-and-references)

---

## 👨‍💻 About Me

I am a cybersecurity professional developing practical capabilities across security operations, detection engineering, offensive security, cloud security, governance, and AI/LLM security.

My goal is to understand how modern systems work, how attackers exploit weaknesses, how defenders detect malicious activity, and how engineering controls reduce risk.

I approach security through four complementary disciplines:

- **Prevent:** Reduce attack surfaces through secure architecture, hardening, least privilege, and defense in depth.
- **Detect:** Identify suspicious activity using telemetry, threat intelligence, analytics, and security monitoring.
- **Validate:** Test security controls through authorized assessments and adversarial testing.
- **Respond:** Investigate findings, preserve evidence, prioritize risk, and verify remediation.

My focus is on reproducible security testing, practical evidence, clear documentation, and continuous improvement.

---

## 🔐 Security Domains

### 1. Security Foundations

- **Networking:** TCP/IP, DNS, HTTP/S, routing, ports, packet analysis, and connectivity troubleshooting.
- **Linux Security:** Users, permissions, processes, services, logs, networking, and system hardening.
- **Windows Security:** Authentication, access controls, PowerShell, event logs, and endpoint protection.
- **Python for Security:** Log analysis, API interaction, automation, and assessment utilities.
- **Security Architecture:** Trust boundaries, defense in depth, identity protection, and secure design.
- **Threat Modeling:** Assets, attack surfaces, abuse cases, threat scenarios, and mitigations.

### 2. SOC and Blue Team

- **SOC Operations:** Alert triage, incident investigation, escalation, and response coordination.
- **Detection Engineering:** Develop, test, tune, and maintain security detection rules.
- **Threat Hunting:** Investigate telemetry using hypotheses and repeatable queries.
- **Incident Response:** Containment, investigation, eradication, recovery, and lessons learned.
- **Digital Forensics:** Examine logs, memory, files, and timelines.
- **Threat Intelligence:** Analyze indicators, adversary behaviors, and threat context.
- **SIEM Engineering:** Ingest, normalize, correlate, and investigate security events.
- **SOAR:** Automate repetitive response workflows with appropriate authorization and oversight.

### 3. Offensive Security and Red Team

- **Vulnerability Assessment:** Discover, validate, prioritize, and report security weaknesses.
- **Web Security:** Authentication, authorization, session management, input validation, and business logic.
- **API Security:** Endpoint authorization, token handling, rate limits, and data exposure.
- **Mobile Security:** Application storage, permissions, network communication, and authentication.
- **Active Directory:** Identity relationships, privilege escalation paths, and configuration weaknesses.
- **Red Teaming:** Conduct scoped adversary simulations to evaluate security controls.
- **Adversary Emulation:** Reproduce selected techniques to measure detection and response.
- **Security Reporting:** Document evidence, impact, remediation, and retest outcomes.

### 4. Cloud and Platform Security

- **Azure Security:** Entra ID, managed identities, RBAC, Key Vault, networking, logging, and resource hardening.
- **AWS Security:** IAM, storage, compute, networking, monitoring, and workload configuration.
- **Multi-Cloud Security:** Consistent identity, configuration, and governance controls.
- **Container Security:** Image scanning, registry protection, runtime security, and least privilege.
- **Kubernetes Security:** RBAC, network policies, secrets, admission controls, and runtime monitoring.
- **Infrastructure as Code:** Detect insecure configuration before deployment.
- **DevSecOps:** Integrate security scanning, policy checks, and remediation into CI/CD pipelines.

### 5. Governance, Risk and Compliance

- **ISO/IEC 27001:** Information security management systems.
- **NIST CSF:** Enterprise cybersecurity risk management.
- **NIST SP 800-53:** Security and privacy controls.
- **CIS Controls:** Prioritized cybersecurity safeguards.
- **OWASP ASVS:** Application security verification requirements.
- **Risk Assessment:** Evaluate threats, vulnerabilities, likelihood, impact, and treatment options.
- **Audit and Compliance:** Collect evidence, assess controls, document gaps, and track remediation.
- **Security Governance:** Define accountability, control ownership, policy, and oversight.

### 6. AI and LLM Security

- **LLM Security:** Prompt injection, jailbreaks, information disclosure, and insecure output handling.
- **Machine Learning Security:** Adversarial inputs, poisoning, model extraction, and inference-time threats.
- **Generative AI Security:** Risks from model-generated text, code, images, and other outputs.
- **RAG Security:** Retrieval permissions, document trust, vector databases, and context isolation.
- **Agent Security:** Tool authorization, memory boundaries, constrained autonomy, and human approval.
- **MCP Security:** Secure client/server integrations and external tool execution.
- **LLM Guardrails:** Input/output validation, policy enforcement, and bypass testing.
- **AI Supply Chain:** Model provenance, dependencies, datasets, artifacts, and serving infrastructure.
- **AI Threat Modeling:** Map AI assets, trust boundaries, abuse cases, and mitigations.
- **AI Governance:** Manage security, privacy, safety, transparency, and accountability throughout the AI lifecycle.

---

## 🧰 Security Tooling and Platforms

*Tools below are a learning and reference catalog. Inclusion does not imply that I have deployed, mastered, or used every tool.*

### Networking and Protocol Analysis

- [Wireshark](https://www.wireshark.org/) — Capture and analyze network packets.
- [TShark](https://www.wireshark.org/docs/man-pages/tshark.html) — Perform command-line packet analysis.
- [tcpdump](https://www.tcpdump.org/) — Capture and filter network traffic.
- [Zeek](https://github.com/zeek/zeek) — Generate structured network security telemetry.
- [Nmap](https://github.com/nmap/nmap) — Discover hosts, ports, and services.
- [Masscan](https://github.com/robertdavidgraham/masscan) — Perform high-speed port discovery within approved scopes.
- [RustScan](https://github.com/RustScan/RustScan) — Accelerate port discovery and integrate with Nmap.
- [Netcat](https://nmap.org/ncat/) — Test network connections and exchange data over sockets.
- [Socat](https://github.com/3ndG4me/socat) — Relay data between network sockets and other endpoints.
- [MTR](https://github.com/traviscross/mtr) — Investigate network paths and packet loss.
- [OpenSSL](https://github.com/openssl/openssl) — Inspect TLS connections and certificate behavior.
- [cURL](https://github.com/curl/curl) — Test HTTP APIs and troubleshoot application connectivity.

### SOC and SIEM

- [Microsoft Sentinel](https://learn.microsoft.com/azure/sentinel/) — Cloud-native SIEM and security operations.
- [Wazuh](https://github.com/wazuh/wazuh) — Security monitoring, endpoint telemetry, and compliance.
- [Security Onion](https://github.com/Security-Onion-Solutions/securityonion) — Network security monitoring and threat hunting.
- [Elastic Security](https://www.elastic.co/security) — Security analytics and investigation.
- [Elasticsearch](https://github.com/elastic/elasticsearch) — Index and search event data.
- [Kibana](https://github.com/elastic/kibana) — Visualize and investigate security telemetry.
- [Graylog](https://github.com/Graylog2/graylog2-server) — Centralize and analyze logs.
- [Splunk](https://www.splunk.com/) — Search, analyze, and correlate machine-generated data.
- [Sigma](https://github.com/SigmaHQ/sigma) — Write portable detection rules.
- [OpenCTI](https://github.com/OpenCTI-Platform/opencti) — Manage and correlate threat intelligence.
- [MISP](https://github.com/MISP/MISP) — Share and analyze threat indicators.
- [TheHive](https://github.com/TheHive-Project/TheHive) — Coordinate security investigations and incident cases.

### Detection Engineering and Adversary Emulation

- [MITRE ATT&CK](https://attack.mitre.org/) — Map adversary behavior to documented tactics and techniques.
- [ATT&CK Navigator](https://github.com/mitre-attack/attack-navigator) — Visualize detection and technique coverage.
- [Atomic Red Team](https://github.com/redcanaryco/atomic-red-team) — Run focused tests to validate security controls.
- [MITRE Caldera](https://github.com/mitre/caldera) — Automate authorized adversary emulation.
- [Elastic Detection Rules](https://github.com/elastic/detection-rules) — Study and develop detection logic.
- [Splunk Security Content](https://github.com/splunk/security_content) — Explore detections and analytic stories.
- [osquery](https://github.com/osquery/osquery) — Query endpoint state using SQL-like queries.
- [Velociraptor](https://github.com/Velocidex/velociraptor) — Collect endpoint evidence and conduct investigations.
- [Chainsaw](https://github.com/WithSecureLabs/chainsaw) — Hunt through Windows event logs.
- [Hayabusa](https://github.com/Yamato-Security/hayabusa) — Detect suspicious activity in Windows event logs.

### Digital Forensics and Mobile Security

- [Volatility 3](https://github.com/volatilityfoundation/volatility3) — Analyze memory images.
- [Autopsy](https://github.com/sleuthkit/autopsy) — Conduct digital forensic investigations.
- [The Sleuth Kit](https://github.com/sleuthkit/sleuthkit) — Examine disk images and file systems.
- [ALEAPP](https://github.com/abrignoni/ALEAPP) — Parse Android forensic artifacts.
- [iLEAPP](https://github.com/abrignoni/iLEAPP) — Parse iOS and iPadOS forensic artifacts.
- [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) — Assess mobile application security.
- [Frida](https://github.com/frida/frida) — Instrument applications for authorized dynamic analysis.
- [JADX](https://github.com/skylot/jadx) — Decompile Android applications for analysis.
- [Apktool](https://github.com/iBotPeaches/Apktool) — Inspect and reverse engineer Android packages.

### Vulnerability Assessment and Web Security

- [Nessus](https://www.tenable.com/products/nessus) — Scan for known vulnerabilities.
- [Greenbone](https://github.com/greenbone) — Assess vulnerabilities using the Greenbone ecosystem.
- [Nuclei](https://github.com/projectdiscovery/nuclei) — Run template-driven security checks.
- [Nuclei Templates](https://github.com/projectdiscovery/nuclei-templates) — Reusable vulnerability and misconfiguration checks.
- [Burp Suite](https://portswigger.net/burp) — Intercept and test web application requests.
- [OWASP ZAP](https://github.com/zaproxy/zaproxy) — Proxy, scan, and test web applications.
- [Amass](https://github.com/owasp-amass/amass) — Map external assets and attack surfaces.
- [Subfinder](https://github.com/projectdiscovery/subfinder) — Discover subdomains using passive sources.
- [httpx](https://github.com/projectdiscovery/httpx) — Probe HTTP services and collect metadata.
- [Katana](https://github.com/projectdiscovery/katana) — Crawl applications to discover endpoints.
- [FFUF](https://github.com/ffuf/ffuf) — Discover web content and test input locations.
- [Gobuster](https://github.com/OJ/gobuster) — Discover directories, files, and DNS records.
- [Feroxbuster](https://github.com/epi052/feroxbuster) — Perform recursive web content discovery.
- [WhatWeb](https://github.com/urbanadventurer/WhatWeb) — Identify web technologies.
- [testssl.sh](https://github.com/testssl/testssl.sh) — Examine TLS and SSL configurations.
- [OWASP Dependency-Check](https://github.com/dependency-check/DependencyCheck) — Identify known vulnerabilities in dependencies.

### API Security

- [Postman](https://www.postman.com/) — Build and execute API test collections.
- [Bruno](https://github.com/usebruno/bruno) — Manage repeatable API requests.
- [Insomnia](https://github.com/Kong/insomnia) — Design and test APIs.
- [Schemathesis](https://github.com/schemathesis/schemathesis) — Test APIs using their schemas.
- [RESTler](https://github.com/microsoft/restler-fuzzer) — Fuzz REST APIs using inferred dependencies.
- [JWT Tool](https://github.com/ticarpi/jwt_tool) — Inspect and test JSON Web Token security.
- [Kiterunner](https://github.com/assetnote/kiterunner) — Discover API routes in authorized assessments.
- [Arjun](https://github.com/s0md3v/Arjun) — Discover hidden HTTP parameters.

### Offensive Security and Active Directory

- [BloodHound](https://github.com/SpecterOps/BloodHound) — Visualize identity relationships and attack paths.
- [SharpHound](https://github.com/SpecterOps/SharpHound) — Collect Active Directory relationship data.
- [Impacket](https://github.com/fortra/impacket) — Inspect and work with network protocols.
- [Rubeus](https://github.com/GhostPack/Rubeus) — Research Kerberos authentication security.
- [PowerSploit](https://github.com/PowerShellMafia/PowerSploit) — Study PowerShell-based security assessment techniques.
- [PingCastle](https://www.pingcastle.com/) — Assess Active Directory security posture.
- [Sliver](https://github.com/BishopFox/sliver) — Authorized adversary simulation framework.
- [Mythic](https://github.com/its-a-feature/Mythic) — Extensible red-team operations framework.
- [Gophish](https://github.com/gophish/gophish) — Conduct authorized phishing-awareness assessments.
- [Metasploit Framework](https://github.com/rapid7/metasploit-framework) — Validate vulnerabilities in controlled environments.

### Cloud, IAM, and Infrastructure as Code

- [Microsoft Defender for Cloud](https://learn.microsoft.com/azure/defender-for-cloud/) — Assess cloud security posture and workload threats.
- [Azure Policy](https://learn.microsoft.com/azure/governance/policy/) — Evaluate resource compliance and enforce organizational rules.
- [Azure Well-Architected Framework](https://learn.microsoft.com/azure/well-architected/) — Review workload design and reliability/security considerations.
- [AWS IAM](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html) — Manage identities and permissions in AWS.
- [Prowler](https://github.com/prowler-cloud/prowler) — Assess cloud configurations against security best practices.
- [ScoutSuite](https://github.com/nccgroup/ScoutSuite) — Audit multi-cloud security configurations.
- [CloudGoat](https://github.com/RhinoSecurityLabs/cloudgoat) — Practice cloud attack scenarios in isolated labs.
- [Pacu](https://github.com/RhinoSecurityLabs/pacu) — Perform authorized AWS security testing.
- [Cloudsplaining](https://github.com/salesforce/cloudsplaining) — Identify risky AWS IAM permissions.
- [Checkov](https://github.com/bridgecrewio/checkov) — Scan infrastructure as code for misconfigurations.
- [Terrascan](https://github.com/tenable/terrascan) — Detect infrastructure policy violations.
- [Trivy](https://github.com/aquasecurity/trivy) — Scan images, dependencies, secrets, and configurations.
- [Steampipe](https://github.com/turbot/steampipe) — Query cloud resources for security analysis.
- [Checkov Policy Reference](https://www.checkov.io/) — Review infrastructure security policies and supported scanners.

### Container and Kubernetes Security

- [Docker](https://github.com/moby/moby) — Build and run containerized workloads.
- [Trivy](https://github.com/aquasecurity/trivy) — Scan container images and configuration.
- [Falco](https://github.com/falcosecurity/falco) — Detect suspicious runtime behavior.
- [Kubescape](https://github.com/kubescape/kubescape) — Assess Kubernetes security posture.
- [kube-bench](https://github.com/aquasecurity/kube-bench) — Check configurations against CIS Kubernetes benchmarks.
- [kube-hunter](https://github.com/aquasecurity/kube-hunter) — Identify Kubernetes security weaknesses in authorized environments.
- [Kyverno](https://github.com/kyverno/kyverno) — Apply policy-as-code to Kubernetes resources.
- [OPA Gatekeeper](https://github.com/open-policy-agent/gatekeeper) — Enforce policy controls for Kubernetes.

### GRC and Security Standards

- [ISO/IEC 27001](https://www.iso.org/standard/27001) — Information security management requirements.
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework) — Organize cybersecurity risk management.
- [NIST SP 800-53](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final) — Security and privacy control catalog.
- [CIS Controls](https://www.cisecurity.org/controls) — Prioritized cybersecurity safeguards.
- [OWASP ASVS](https://owasp.org/www-project-application-security-verification-standard/) — Application security verification requirements.
- [OWASP SAMM](https://owasp.org/www-project-samm/) — Software assurance maturity model.
- [OWASP WSTG](https://owasp.org/www-project-web-security-testing-guide/) — Web application security testing guidance.
- [OWASP Threat Dragon](https://owasp.org/www-project-threat-dragon/) — Create and document threat models.
- [FAIR Institute](https://www.fairinstitute.org/) — Quantitative information risk analysis resources.
- [COBIT](https://www.isaca.org/resources/cobit) — Enterprise IT governance and management.

---

## 🤖 AI Security Tooling

*These tools serve different purposes: vulnerability probing, red-team orchestration, evaluation, application guardrails, and monitoring. They should not be treated as interchangeable.*

### LLM Vulnerability Scanning and Red Teaming

- [Garak](https://github.com/NVIDIA/garak) — Probe LLMs for jailbreaks, prompt injection, data leakage, and other weaknesses.
- [Microsoft PyRIT](https://github.com/Azure/PyRIT) — Orchestrate adversarial testing of generative AI systems.
- [Promptfoo](https://github.com/promptfoo/promptfoo) — Evaluate prompts, models, and application security through repeatable tests.
- [Strix](https://github.com/usestrix/strix) — Use AI-assisted agents to investigate application vulnerabilities.
- [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) — Build and run model evaluations.
- [DeepTeam](https://github.com/confident-ai/deepteam) — Automate LLM application red-team testing.
- [Adversarial Robustness Toolbox](https://github.com/Trusted-AI/adversarial-robustness-toolbox) — Research adversarial attacks and defenses in machine learning.
- [CyberSecEval / Purple Llama](https://github.com/meta-llama/PurpleLlama) — Explore cybersecurity evaluations and LLM safety resources.
- [Microsoft AI Red Team](https://learn.microsoft.com/en-us/security/ai-red-team/) — Guidance for AI red teaming and adversarial assessment.
- [Microsoft Foundry AI Red Teaming](https://learn.microsoft.com/en-us/azure/foundry/concepts/ai-red-teaming-agent) — Explore automated probing and evaluation for supported AI applications.

### AI Evaluation and Quality Assurance

- [OpenAI Evals](https://github.com/openai/evals) — Create evaluations for model behavior.
- [DeepEval](https://github.com/confident-ai/deepeval) — Test LLM application quality and selected security risks.
- [Ragas](https://github.com/vibrantlabsai/ragas) — Evaluate retrieval and generation quality in RAG systems.
- [TruLens](https://github.com/truera/trulens) — Evaluate and observe LLM applications.
- [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) — Define evaluation tasks, solvers, and scoring methods.
- [Promptfoo](https://github.com/promptfoo/promptfoo) — Run comparative evaluations and security regression tests.

### LLM Guardrails and Application Protection

- [NVIDIA NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) — Add programmable controls to LLM conversations and workflows.
- [Guardrails AI](https://github.com/guardrails-ai/guardrails) — Validate inputs, outputs, and structured responses.
- [LLM Guard](https://github.com/protectai/llm-guard) — Explore scanners for input/output risks and sensitive data.
- [Rebuff](https://github.com/protectai/rebuff) — Research prompt-injection detection approaches; verify current maintenance status.
- [Meta Purple Llama](https://github.com/meta-llama/PurpleLlama) — Explore generative AI safety and cybersecurity evaluation resources.
- [Llama Guard resources](https://github.com/meta-llama/PurpleLlama) — Study safety-classification approaches.
- [LlamaFirewall resources](https://github.com/meta-llama/PurpleLlama) — Explore protections for prompt injection and agentic workflows.
- [CodeShield resources](https://github.com/meta-llama/PurpleLlama) — Explore generated-code security resources.
- [Microsoft Azure AI Content Safety](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/overview) — Review content safety capabilities for supported AI applications.

### AI Security Research and Model Testing

- [ModelScan](https://github.com/protectai/modelscan) — Scan supported machine-learning model artifacts for unsafe serialized code.
- [Model Verifier](https://github.com/modelscan/model-verifier) — Perform black-box verification of supported model gateways.
- [Fickling](https://github.com/trailofbits/fickling) — Analyze Python pickle-based model serialization risks.
- [HiddenLayer resources](https://hiddenlayer.com/) — Explore machine-learning security research and protection.
- [Hugging Face Transformers](https://github.com/huggingface/transformers) — Study and use transformer models.
- [Hugging Face Safetensors](https://github.com/huggingface/safetensors) — Work with a tensor format designed to avoid pickle-based loading risks.
- [MLflow](https://github.com/mlflow/mlflow) — Track experiments and manage model lifecycle workflows.

---

## 🛡️ LLM Guardrails Security

Guardrails are application-level controls that inspect, validate, restrict, or audit model interactions. They reduce risk but do not independently guarantee security.

### Input and Prompt Security

- **Input validation:** Reject malformed or prohibited inputs before sensitive processing.
- **Prompt-injection detection:** Identify attempts to override trusted instructions or manipulate application behavior.
- **Jailbreak resistance:** Evaluate whether adversarial inputs bypass intended safety policies.
- **Sensitive-data detection:** Identify credentials, personal information, and confidential data.
- **Context isolation:** Separate trusted instructions from untrusted user input and retrieved content.
- **Rate and resource limits:** Reduce abuse and resource-exhaustion risk.
- **Input normalization:** Handle unexpected formats and encoding consistently.

### Output and Policy Enforcement

- **Output validation:** Check generated responses for prohibited content and sensitive data.
- **Structured-output validation:** Confirm generated JSON or other structured data follows a defined schema.
- **Policy enforcement:** Apply deterministic application rules independently of model instructions.
- **Data-loss prevention:** Reduce accidental disclosure of confidential information.
- **Refusal validation:** Verify prohibited requests are handled appropriately without unnecessarily blocking legitimate requests.
- **Unsafe output handling:** Prevent generated content from being executed or rendered unsafely.
- **Fail-safe behavior:** Define safe behavior when a guardrail or dependency fails.

### Tool-Call and Agent Guardrails

- **Tool authorization:** Permit only approved tools and operations.
- **Argument validation:** Validate tool parameters before execution.
- **Least privilege:** Restrict agent credentials to the minimum required resources.
- **Human approval:** Require authorization for sensitive or irreversible actions.
- **Execution isolation:** Restrict filesystem, network, process, and resource access.
- **Audit logging:** Record policy decisions, tool calls, failures, and approvals.

### Guardrails Security Testing

- Test bypass resistance using approved adversarial cases.
- Measure false positives against legitimate requests.
- Verify independent pre-inference and post-inference checks.
- Test timeout, exception, and unavailable-dependency behavior.
- Validate status codes and response schemas.
- Check that sensitive values are not exposed in responses or logs.
- Preserve timestamps, request/response evidence, and relevant traces.
- Retest known failures after mitigation or configuration changes.

---

## 🎯 AI Red Teaming and Adversarial Testing

AI red teaming tests whether an AI system can be manipulated, misused, or made to violate documented security requirements.

### Threat Scenarios

- **Direct prompt injection:** User input attempts to override trusted instructions.
- **Indirect prompt injection:** Untrusted documents, web pages, or tool outputs influence the model.
- **Jailbreaks:** Adversarial inputs attempt to bypass safety controls.
- **Sensitive-data leakage:** Private information appears in generated responses.
- **System-prompt exposure:** Confidential instructions or implementation details are disclosed.
- **Insecure output handling:** Model output triggers unsafe downstream processing.
- **Excessive agency:** An agent performs actions outside its approved scope.
- **Tool misuse:** Tools are called with unauthorized operations or unsafe arguments.
- **RAG manipulation:** Malicious documents influence retrieval or generation.
- **Denial of service:** Expensive or repeated requests exhaust resources.
- **Poisoning:** Manipulated training, fine-tuning, or evaluation data affects model behavior.
- **Supply-chain compromise:** Untrusted model artifacts or dependencies introduce risk.

### Testing Methodology

1. Define authorization, test objectives, and safety constraints.
2. Establish a baseline using benign inputs.
3. Execute controlled adversarial test cases.
4. Compare observed behavior with documented expectations.
5. Record reproducible evidence and impact.
6. Assess whether the weakness is in the model, application, tool, or configuration.
7. Recommend controls and validate them through retesting.

### Useful Resources

- [OWASP Top 10 for LLM Applications](https://genai.owasp.org/llm-top-10/)
- [OWASP Top 10 for Agentic Applications](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/)
- [MITRE ATLAS](https://atlas.mitre.org/)
- [Microsoft AI Red Team](https://learn.microsoft.com/en-us/security/ai-red-team/)
- [Garak](https://github.com/NVIDIA/garak)
- [PyRIT](https://github.com/Azure/PyRIT)
- [Promptfoo](https://github.com/promptfoo/promptfoo)

---

## 📚 RAG Security

Retrieval-Augmented Generation combines an LLM with external information retrieval. Security depends on the model, source documents, retrieval logic, authorization, and data storage.

### RAG Security Risks

- **Document poisoning:** Malicious or misleading content enters the knowledge base.
- **Indirect prompt injection:** Retrieved content attempts to manipulate model behavior.
- **Cross-user data leakage:** A user retrieves information belonging to another user or tenant.
- **Broken access control:** Retrieval ignores document-level permissions.
- **Vector-store exposure:** Sensitive data or metadata becomes accessible to unauthorized parties.
- **Retrieval manipulation:** Adversarial content changes which documents are returned.
- **Data provenance failure:** The application cannot establish where retrieved information originated.
- **Insecure ingestion:** Documents are processed without sufficient validation.
- **Citation and grounding failures:** Responses misrepresent sources or expose unauthorized content.

### RAG Engineering and Security Tools

- [LangChain](https://github.com/langchain-ai/langchain) — Build LLM and retrieval workflows.
- [LlamaIndex](https://github.com/run-llama/llama_index) — Connect LLMs to external data sources.
- [Haystack](https://github.com/deepset-ai/haystack) — Build retrieval and question-answering pipelines.
- [Chroma](https://github.com/chroma-core/chroma) — Store and retrieve vector embeddings.
- [Qdrant](https://github.com/qdrant/qdrant) — Perform vector similarity search.
- [Weaviate](https://github.com/weaviate/weaviate) — Build vector-search applications.
- [Milvus](https://github.com/milvus-io/milvus) — Store and search vector data.
- [Ragas](https://github.com/vibrantlabsai/ragas) — Evaluate retrieval and generation quality.
- [TruLens](https://github.com/truera/trulens) — Evaluate and observe RAG workflows.
- [DeepEval](https://github.com/confident-ai/deepeval) — Test LLM and RAG behavior.
- [Promptfoo](https://github.com/promptfoo/promptfoo) — Run repeatable security evaluations.

### RAG Security Lab Objectives

1. Build an isolated RAG application using synthetic documents.
2. Define document-level and user-level access requirements.
3. Test prompt injection through retrieved content.
4. Validate retrieval permissions and tenant isolation.
5. Test whether confidential documents appear in unauthorized responses.
6. Record evidence and validate mitigations.

---

## 🤖 AI Agent Security

AI agents can plan tasks, invoke tools, and take actions. Security must constrain their permissions and verify sensitive operations.

### Agent Security Risks

- Excessive agency and unauthorized actions.
- Tool abuse and unsafe arguments.
- Indirect prompt injection through external content.
- Memory poisoning or cross-session information leakage.
- Credential exposure in context, logs, or tool results.
- Unsafe delegation between agents.
- Insecure code or command execution.
- Approval bypass for sensitive operations.
- Unverified outputs from connected agents or tools.

### Agent Frameworks and Resources

- [LangGraph](https://github.com/langchain-ai/langgraph) — Build stateful, controllable agent workflows.
- [AutoGen](https://github.com/microsoft/autogen) — Experiment with multi-agent applications.
- [CrewAI](https://github.com/crewAIInc/crewAI) — Orchestrate role-based agent teams.
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) — Integrate models, plugins, and application logic.
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) — Build agent applications with tools, handoffs, and tracing.
- [LangChain](https://github.com/langchain-ai/langchain) — Connect LLMs with tools and data.

### Agent Security Controls

- Explicit tool allowlists and per-tool authorization.
- Least-privilege credentials and isolated execution.
- Validation of untrusted content and tool parameters.
- Human approval for sensitive or irreversible actions.
- Bounded iterations, timeouts, and resource limits.
- Auditable decisions, tool calls, approvals, and outcomes.
- Tests for memory leakage, unsafe delegation, and unauthorized actions.

---

## 🔌 MCP Security

The Model Context Protocol connects AI applications with external tools and data sources. Each connection introduces trust boundaries that need explicit security controls.

### MCP Security Risks

- **Tool poisoning:** Malicious instructions are embedded in tool descriptions or outputs.
- **Prompt injection:** Untrusted MCP-provided content influences agent behavior.
- **Tool impersonation:** An untrusted integration presents itself as legitimate.
- **Excessive permissions:** An MCP server exposes capabilities beyond requirements.
- **Credential leakage:** Tokens or secrets appear in configuration, logs, or responses.
- **Cross-tool escalation:** One integration influences another tool's actions.
- **Supply-chain compromise:** A compromised server or dependency introduces malicious behavior.
- **Configuration drift:** A previously trusted tool changes its behavior or description.
- **Unsafe local execution:** Filesystem or command tools exceed intended boundaries.

### MCP Security Tools and References

- [OWASP MCP Top 10](https://owasp.org/projects/mcp-top-10) — Security risks affecting MCP-enabled systems.
- [OWASP MCP Security Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/MCP_Security_Cheat_Sheet.html) — Practical MCP security guidance.
- [MCP-Scan](https://github.com/invariantlabs-ai/mcp-scan) — Inspect MCP integrations for risky tool descriptions and related threats.
- [Official MCP Organization](https://github.com/modelcontextprotocol) — Protocol ecosystem and official repositories.
- [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) — Build MCP clients and servers in Python.
- [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) — Build MCP clients and servers in TypeScript.
- [FastMCP](https://github.com/jlowin/fastmcp) — Develop MCP applications using a higher-level Python framework.

### MCP Security Lab Objectives

1. Create an isolated MCP test environment with non-sensitive data.
2. Inventory servers, tools, permissions, and exposed resources.
3. Inspect server configurations and tool descriptions.
4. Test untrusted tool output and prompt-injection scenarios.
5. Validate authentication, authorization, and secret handling.
6. Verify execution boundaries and tool restrictions.
7. Document findings and retest after remediation.

---

## 📦 AI Supply-Chain and Model Security

Secure the components used to build, distribute, evaluate, and deploy AI systems, including model artifacts, dependencies, datasets, and serving infrastructure.

### Key Risks and Controls

- **Model provenance:** Record model origin, publisher, version, and integrity information.
- **Artifact scanning:** Identify potentially unsafe serialized model files.
- **Dependency security:** Detect vulnerable or compromised packages.
- **Dataset integrity:** Validate data sources, permissions, and unexpected modifications.
- **Model access control:** Restrict access to weights, artifacts, and sensitive training data.
- **Inference security:** Protect serving endpoints, credentials, and execution environments.
- **CI/CD security:** Integrate security checks into AI development pipelines.
- **Container hardening:** Minimize privileges and scan model-serving images.
- **Secrets management:** Keep credentials outside source code and logs.
- **AI Bill of Materials (AI BOM):** Explore inventories of models, datasets, dependencies, and AI components to improve provenance and risk visibility.

### Supply-Chain Tools

- [ModelScan](https://github.com/protectai/modelscan) — Scan supported ML model artifacts for unsafe serialized code.
- [Fickling](https://github.com/trailofbits/fickling) — Analyze pickle-based serialization risks.
- [Trivy](https://github.com/aquasecurity/trivy) — Scan images, dependencies, secrets, and configurations.
- [Checkov](https://github.com/bridgecrewio/checkov) — Validate infrastructure and deployment configuration.
- [DVC](https://github.com/iterative/dvc) — Version datasets and machine-learning artifacts.
- [MLflow](https://github.com/mlflow/mlflow) — Track experiments and manage model lifecycle workflows.
- [Kubeflow](https://github.com/kubeflow/kubeflow) — Orchestrate machine-learning workflows.
- [BentoML](https://github.com/bentoml/BentoML) — Package and serve machine-learning models.
- [KServe](https://github.com/kserve/kserve) — Deploy inference services on Kubernetes.
- [Seldon Core](https://github.com/SeldonIO/seldon-core) — Deploy and manage machine-learning inference workloads.
- [Hugging Face Safetensors](https://github.com/huggingface/safetensors) — Use a tensor format designed to avoid pickle-based loading risks.

---

## 📊 AI Security Monitoring and AI SOC

AI security monitoring combines application telemetry, model events, identity activity, and security detections to investigate threats against AI systems.

### Monitoring Objectives

- **Inference monitoring:** Track model requests, errors, usage, and policy violations.
- **Identity monitoring:** Detect unexpected access to models, data, and agent tools.
- **Guardrail telemetry:** Record blocked requests, bypass attempts, and validation failures.
- **Data-access monitoring:** Investigate suspicious retrieval and cross-tenant access.
- **Agent activity monitoring:** Audit tool calls, permissions, approvals, and action outcomes.
- **Threat correlation:** Connect AI events with endpoint, identity, cloud, and network telemetry.
- **Incident response:** Preserve evidence and coordinate containment and recovery.

### Relevant Tools

- [Microsoft Sentinel](https://learn.microsoft.com/azure/sentinel/) — Correlate security events and investigate incidents.
- [Wazuh](https://github.com/wazuh/wazuh) — Monitor endpoints, logs, and compliance signals.
- [Elastic Security](https://www.elastic.co/security) — Investigate telemetry and develop detections.
- [Sigma](https://github.com/SigmaHQ/sigma) — Express portable detection logic.
- [OpenCTI](https://github.com/OpenCTI-Platform/opencti) — Organize threat intelligence.
- [MISP](https://github.com/MISP/MISP) — Manage and share threat indicators.
- [TheHive](https://github.com/TheHive-Project/TheHive) — Coordinate incident investigations.
- [Shuffle](https://github.com/Shuffle/Shuffle) — Automate security operations workflows.
- [StackStorm](https://github.com/StackStorm/st2) — Automate event-driven operations.
- [Cortex](https://github.com/TheHive-Project/Cortex) — Automate analysis of security observables.

---

## 🧠 AI / LLM Engineering

Understanding AI architecture helps security assessments reflect how applications actually process data and execute actions.

### Models, Frameworks, and Serving

- [Hugging Face Transformers](https://github.com/huggingface/transformers) — Use and study transformer models.
- [Ollama](https://github.com/ollama/ollama) — Run supported models locally.
- [vLLM](https://github.com/vllm-project/vllm) — Serve language models efficiently.
- [LM Studio](https://lmstudio.ai/) — Experiment with local language models.
- [Open WebUI](https://github.com/open-webui/open-webui) — Operate a self-hosted interface for supported AI backends.
- [LangChain](https://github.com/langchain-ai/langchain) — Compose LLM application workflows.
- [LangGraph](https://github.com/langchain-ai/langgraph) — Build stateful agent workflows.
- [LlamaIndex](https://github.com/run-llama/llama_index) — Connect models to external data.
- [Haystack](https://github.com/deepset-ai/haystack) — Build retrieval and question-answering pipelines.

### Vector Databases

- [Chroma](https://github.com/chroma-core/chroma) — Store and retrieve embeddings.
- [Qdrant](https://github.com/qdrant/qdrant) — Perform vector similarity search.
- [Weaviate](https://github.com/weaviate/weaviate) — Build vector-search applications.
- [Milvus](https://github.com/milvus-io/milvus) — Operate vector search at scale.
- [pgvector](https://github.com/pgvector/pgvector) — Add vector similarity search to PostgreSQL.

### MLOps and LLMOps

- [MLflow](https://github.com/mlflow/mlflow) — Track experiments and manage models.
- [Kubeflow](https://github.com/kubeflow/kubeflow) — Orchestrate ML pipelines.
- [DVC](https://github.com/iterative/dvc) — Version datasets and reproducible workflows.
- [Apache Airflow](https://github.com/apache/airflow) — Schedule and orchestrate data pipelines.
- [BentoML](https://github.com/bentoml/BentoML) — Package models for production serving.
- [KServe](https://github.com/kserve/kserve) — Operate inference services on Kubernetes.

---

## ⚖️ AI Governance, Risk and Compliance

AI governance establishes accountability, risk ownership, documented controls, and evidence that AI systems meet applicable organizational and regulatory requirements.

### AI Governance Frameworks

- [ISO/IEC 42001](https://www.iso.org/standard/81230.html) — AI management system requirements.
- [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework) — Manage AI risks through Govern, Map, Measure, and Manage.
- [NIST AI 600-1: Generative AI Profile](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf) — Apply AI risk-management guidance to generative AI.
- [NIST AI Resource Center](https://airc.nist.gov/) — Explore AI risk-management resources.
- [EU AI Act](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai) — Review EU regulatory requirements for covered AI systems.
- [OECD AI Principles](https://oecd.ai/en/ai-principles) — Explore principles for trustworthy AI.
- [MIT AI Risk Repository](https://airisk.mit.edu/) — Research documented AI risk categories.
- [AI Verify](https://github.com/aisingapore/AI-Verify) — Explore AI testing and responsible-AI verification resources.

### AI Security Frameworks and Guidance

- [OWASP Top 10 for LLM Applications](https://genai.owasp.org/llm-top-10/) — Understand prominent LLM application risks.
- [OWASP Top 10 for Agentic Applications](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/) — Review risks associated with autonomous and tool-using AI systems.
- [OWASP MCP Top 10](https://owasp.org/projects/mcp-top-10) — Understand security risks in MCP-enabled systems.
- [OWASP AI Security Verification Standard](https://owasp.org/www-project-ai-security-verification-standard/) — Explore AI system security verification requirements.
- [OWASP GenAI Security Project](https://genai.owasp.org/) — Find generative AI security guidance.
- [MITRE ATLAS](https://atlas.mitre.org/) — Study adversary tactics and techniques targeting AI.
- [MITRE ATT&CK](https://attack.mitre.org/) — Map adversary behavior in enterprise environments.
- [Microsoft AI Red Team](https://learn.microsoft.com/en-us/security/ai-red-team/) — Review AI red-team methods and guidance.
- [Azure AI Foundry](https://learn.microsoft.com/en-us/azure/ai-foundry/) — Explore AI application development and evaluation resources.

### Threat Modeling Methodologies

- **STRIDE:** Spoofing, tampering, repudiation, information disclosure, denial of service, and elevation of privilege.
- **PASTA:** Risk-centric application threat modeling.
- **DREAD:** Historical threat-prioritization model.
- **OCTAVE:** Organizational asset and security risk assessment.
- **Trike:** Risk-based threat modeling.
- **VAST:** Scalable threat modeling for applications and infrastructure.
- **LINDDUN:** Privacy threat modeling.
- **OWASP Threat Dragon:** [Threat-modeling tool](https://owasp.org/www-project-threat-dragon/).
- **NIST CSF:** [Cybersecurity risk-management framework](https://www.nist.gov/cyberframework).
- **NIST SP 800-53:** [Security and privacy controls](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final).
- **NIST SP 800-61:** [Incident response guidance](https://csrc.nist.gov/pubs/sp/800/61/r3/final).
- **NIST SP 800-207:** [Zero Trust Architecture](https://csrc.nist.gov/pubs/sp/800/207/final).

### Enterprise GRC and Controls

- **ISO/IEC 27001:** Information security management.
- **ISO/IEC 27002:** Information security control guidance.
- **ISO/IEC 42001:** AI management systems.
- **NIST AI RMF:** AI risk management.
- **NIST CSF:** Enterprise cybersecurity risk management.
- **CIS Controls:** Prioritized security safeguards.
- **SOC 2:** Assessment of applicable organizational controls.
- **GDPR:** Applicable personal-data protection and processing obligations.
- **FAIR:** Quantitative information risk analysis.
- **COBIT:** Enterprise IT governance and management.

Frameworks and standards should be selected based on system scope, organizational needs, and applicable obligations; listing them does not imply certification or compliance.

---

## 🧪 Hands-On Security Labs

Each lab should produce repeatable exercises, evidence, documented findings, and validated remediation—not merely a tool installation.

- **Kali Linux Lab:** Learn networking, enumeration, and authorized penetration testing.
- **Networking Lab:** Capture traffic and investigate connectivity and suspicious communications.
- **Web Security Lab:** Test authentication, authorization, input handling, and common vulnerabilities.
- **API Security Lab:** Validate permissions, token handling, input validation, and data exposure.
- **Mobile Security Lab:** Analyze mobile applications using appropriate test environments.
- **Active Directory Lab:** Explore directory configuration, authentication, and privilege relationships.
- **Cloud Security Lab:** Assess IAM permissions, cloud configuration, logging, and least privilege.
- **Detection Engineering Lab:** Build, test, and tune detection rules.
- **Threat Hunting Lab:** Investigate telemetry using documented hypotheses.
- **Incident Response Lab:** Practice triage, evidence preservation, containment, and recovery.
- **SIEM Lab:** Ingest, normalize, correlate, and query security telemetry.
- **AI / LLM Security Lab:** Test model behavior, prompt handling, and safety controls.
- **RAG Security Lab:** Validate retrieval permissions, document trust, and injection resistance.
- **AI Agent Security Lab:** Test tool authorization, action boundaries, and approval mechanisms.
- **MCP Security Lab:** Inspect server configurations, permissions, and untrusted tool responses.
- **Guardrails Security Lab:** Test input/output validation, policy enforcement, and bypass resistance.

---

## 🎯 Current Mission and Focus

Building practical expertise toward becoming an **AI Security Engineer** by combining:

- Security Operations and SOC.
- Detection Engineering and Threat Hunting.
- Vulnerability Assessment and Penetration Testing.
- Red Teaming and Adversary Emulation.
- Cloud Security and DevSecOps.
- Governance, Risk and Compliance.
- AI / LLM Security and AI Red Teaming.
- Secure AI Systems Engineering.

### Current Focus Areas

- **LLM Security Testing:** Evaluate model and application behavior through controlled tests.
- **Guardrails Security:** Validate policy enforcement, input/output checks, and failure handling.
- **RAG Security:** Test document access, retrieval behavior, and trust boundaries.
- **MCP Security:** Investigate tool integrations, permissions, and untrusted outputs.
- **AI Agent Security:** Restrict autonomous behavior and validate authorization controls.
- **Detection Engineering:** Translate threat behavior into testable detections.
- **Security Automation:** Build repeatable assessment and response workflows.
- **Secure AI Architecture:** Apply least privilege, isolation, defense in depth, and auditability.

---

## 📚 Continuous Learning

My learning approach is based on five steps:

1. Understand the underlying technology.
2. Identify relevant threats and trust boundaries.
3. Reproduce security issues in an authorized lab.
4. Develop and validate appropriate mitigations.
5. Document results so they can be reproduced and reviewed.

The portfolio documents my progression across cybersecurity, AI security, detection engineering, cloud security, and secure AI systems.

---

## 🗺️ Learning Roadmap

### Completed

- Repository foundation and initial architecture.
- Initial Garak-based LLM security assessment.

### In Progress

- Improving project documentation and assessment workflows.
- Expanding practical knowledge of AI security testing and defensive controls.

### Planned

- Develop a reproducible RAG security assessment module.
- Evaluate guardrail effectiveness against selected adversarial test cases.
- Build AI agent security tests for tool authorization and unsafe actions.
- Research MCP configuration and tool-poisoning risks.
- Add automated reporting and evidence collection.
- Explore detections for AI application telemetry.
- Document remediation and regression-testing workflows.
- Develop end-to-end AI security assessment case studies.

*Progress labels will be updated as work actually starts or finishes. Planned work is not presented as completed implementation.*

---

## 🤝 Responsible Testing

All security assessments and demonstrations must be performed only against systems I own or have explicit authorization to test.

- Define and follow an approved scope.
- Use isolated labs and non-sensitive test data wherever possible.
- Avoid exposing credentials, tokens, personal information, or confidential prompts.
- Do not run destructive tests against production systems without explicit authorization.
- Record findings accurately and distinguish demonstrated vulnerabilities from theoretical risks.
- Validate proposed mitigations and document residual risk.
- Respect software licenses, disclosure requirements, and applicable laws.

---

## 📎 Project Links and References

### My Project

- [AI Sentinel — AI Security Red Team Lab](https://github.com/LOKESH-AISECURITY/ai-security-red-team-lab)

### AI Security

- [OWASP GenAI Security Project](https://genai.owasp.org/)
- [OWASP Top 10 for LLM Applications](https://genai.owasp.org/llm-top-10/)
- [OWASP Top 10 for Agentic Applications](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/)
- [OWASP MCP Top 10](https://owasp.org/projects/mcp-top-10)
- [MITRE ATLAS](https://atlas.mitre.org/)
- [NIST AI RMF](https://www.nist.gov/itl/ai-risk-management-framework)
- [NIST Generative AI Profile](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf)

### Testing Tools

- [Garak](https://github.com/NVIDIA/garak)
- [Microsoft PyRIT](https://github.com/Azure/PyRIT)
- [Promptfoo](https://github.com/promptfoo/promptfoo)
- [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails)
- [ModelScan](https://github.com/protectai/modelscan)
- [MCP-Scan](https://github.com/invariantlabs-ai/mcp-scan)

---

**AI Sentinel — Learn. Test. Detect. Defend. Secure AI.**
