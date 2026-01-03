<script lang="ts">
</script>

<div class="experience">
	<div class="job">
		<div class="job-header">
			<h3>Knox Systems - DevOps Engineer</h3>
		</div>

		<div class="project">
			<p class="project-title">Enterprise Privileged Access Management Platform</p>
			<div style="padding-left: 20px;">
				<div class="field-row">
					<input id="knox1" type="radio" name="knox-pam" disabled />
					<label for="knox1"
						>Architected multi-account Terraform infrastructure managing 23 AWS accounts with 6
						reusable modules (backend, compute, keypair, networking, pam, github-oidc), implementing
						S3 remote state with DynamoDB locking and KMS encryption</label
					>
				</div>
				<div class="field-row">
					<input id="knox2" type="radio" name="knox-pam" disabled />
					<label for="knox2"
						>Deployed Keeper Connection Manager across 23 client AWS accounts with OTT-init gateway
						bootstrapping, Elastic IP pinning for static addressing, and CloudWatch monitoring with
						SNS alerting</label
					>
				</div>
				<div class="field-row">
					<input id="knox3" type="radio" name="knox-pam" disabled />
					<label for="knox3"
						>Built serverless AWS console proxy using Lambda, API Gateway, and DynamoDB enabling
						federated console access via SSM Parameter Store secrets with dynamic IP lookup and
						Checkov security scanning</label
					>
				</div>
			</div>
		</div>

		<div class="project">
			<p class="project-title">Kubernetes Container Platform & GitOps</p>
			<div style="padding-left: 20px;">
				<div class="field-row">
					<input id="knox4" type="radio" name="knox-k8s" disabled />
					<label for="knox4"
						>Designed production EKS cluster infrastructure with ArgoCD GitOps (Helm v5.51.6),
						Grafana monitoring, ECR integration, ACM certificates, ALB ingress controller, and
						Karpenter node autoscaling</label
					>
				</div>
				<div class="field-row">
					<input id="knox5" type="radio" name="knox-k8s" disabled />
					<label for="knox5"
						>Executed zero-downtime EKS cluster upgrades (1.31 to 1.32) across multiple production
						environments managing add-on version compatibility (vpc-cni, coredns, kube-proxy,
						ebs-csi-driver) and ECR endpoint configurations</label
					>
				</div>
			</div>
		</div>

		<div class="project">
			<p class="project-title">FedRAMP Compliance & Security Remediation</p>
			<div style="padding-left: 20px;">
				<div class="field-row">
					<input id="knox6" type="radio" name="knox-fedramp" disabled />
					<label for="knox6"
						>Developed 19-module Terraform architecture for FedRAMP Moderate OutSystems platform
						including WAF, VPC endpoints, SSM automation, compliance controls, and 7-phase GitHub
						Actions CI/CD pipeline with OIDC authentication</label
					>
				</div>
				<div class="field-row">
					<input id="knox7" type="radio" name="knox-fedramp" disabled />
					<label for="knox7"
						>Led FedRAMP High security remediation achieving 81% resolution rate (13 of 16 findings)
						including NACL hardening, EC2 IMDS hop limit restrictions, and security group analysis
						with documented compensating controls</label
					>
				</div>
				<div class="field-row">
					<input id="knox8" type="radio" name="knox-fedramp" disabled />
					<label for="knox8"
						>Conducted FIPS compliance audit across 71 AWS accounts identifying 25 Linux instances
						requiring cryptographic module enablement and documenting SSM agent deployment gaps</label
					>
				</div>
				<div class="field-row">
					<input id="knox9" type="radio" name="knox-fedramp" disabled />
					<label for="knox9"
						>Automated CrowdStrike Falcon sensor deployment via Terraform and AWS Systems Manager
						enabling consistent endpoint security posture across enterprise cloud infrastructure</label
					>
				</div>
			</div>
		</div>

		<div class="project">
			<p class="project-title">Internal Tooling</p>
			<div style="padding-left: 20px;">
				<div class="field-row">
					<input id="knox10" type="radio" name="knox-tooling" disabled />
					<label for="knox10"
						>Built Go-based CLI tool using Cobra framework and AWS SDK v2 with OIDC device
						authorization flow, fuzzy finder for account/role selection, token caching, and
						multi-architecture releases (darwin/linux, amd64/arm64)</label
					>
				</div>
			</div>
		</div>
	</div>

	<div class="separator"></div>

	<div class="job">
		<div class="job-header">
			<h3>Lockheed Martin - Software Engineer II</h3>
		</div>

		<div class="project">
			<p class="project-title">Java Event Processing Platform - Backend Developer</p>
			<div style="padding-left: 20px;">
				<div class="field-row">
					<input id="lm1" type="radio" name="lm-java" disabled />
					<label for="lm1"
						>Built Spring Boot microservices to process high-throughput asynchronous events using
						reactive patterns, reducing end-to-end message latency by 10% under peak load conditions</label
					>
				</div>
				<div class="field-row">
					<input id="lm2" type="radio" name="lm-java" disabled />
					<label for="lm2"
						>Integrated ActiveMQ message broker for real-time event transmission, implementing dead
						letter queues and retry logic ensuring fault-tolerant communication with Unity frontend
						consumers</label
					>
				</div>
				<div class="field-row">
					<input id="lm3" type="radio" name="lm-java" disabled />
					<label for="lm3"
						>Engineered protocol-buffer serialization pipeline with custom correlation logic for
						efficient parsing, routing, and deduplication of high-volume data streams across
						distributed services</label
					>
				</div>
			</div>
		</div>

		<div class="project">
			<p class="project-title">
				Tactical Edge Health & Status Monitoring System - Full-Stack Developer
			</p>
			<div style="padding-left: 20px;">
				<div class="field-row">
					<input id="lm4" type="radio" name="lm-edge" disabled />
					<label for="lm4"
						>Led internal R&D team to architect and develop Android plugin dashboard providing
						real-time system health analytics with customizable alerting thresholds and historical
						trend visualization</label
					>
				</div>
				<div class="field-row">
					<input id="lm5" type="radio" name="lm-edge" disabled />
					<label for="lm5"
						>Implemented Python aggregator-collector framework that probes edge devices using custom
						REST APIs and ActiveMQ, aggregating telemetry from distributed hardware deployments</label
					>
				</div>
				<div class="field-row">
					<input id="lm6" type="radio" name="lm-edge" disabled />
					<label for="lm6"
						>Delivered traffic-light UI overlay to intuitively represent system health states and
						recommended remediation actions based on real-time data collected from field-deployed
						hardware via messaging streams</label
					>
				</div>
			</div>
		</div>

		<div class="project">
			<p class="project-title">Azure-Based GIS Tracking Interface - DevOps Engineer</p>
			<div style="padding-left: 20px;">
				<div class="field-row">
					<input id="lm7" type="radio" name="lm-azure" disabled />
					<label for="lm7"
						>Developed React-based geospatial dashboard displaying real-time aircraft telemetry with
						map overlays, track history, and filtering capabilities consuming ActiveMQ track data
						sources</label
					>
				</div>
				<div class="field-row">
					<input id="lm8" type="radio" name="lm-azure" disabled />
					<label for="lm8"
						>Deployed scalable Azure environments using Terraform and Helm charts, implementing
						auto-scaling policies and optimizing compute costs across dev/staging/production
						environments</label
					>
				</div>
				<div class="field-row">
					<input id="lm9" type="radio" name="lm-azure" disabled />
					<label for="lm9"
						>Configured Azure Application Gateway with SSL termination, WAF rules, and traffic
						routing for secure, load-balanced access to containerized microservices</label
					>
				</div>
			</div>
		</div>

		<div class="project">
			<p class="project-title">AWS GovCloud DevSecOps Infrastructure - DevOps Engineer</p>
			<div style="padding-left: 20px;">
				<div class="field-row">
					<input id="lm10" type="radio" name="lm-govcloud" disabled />
					<label for="lm10"
						>Spearheaded Agile DevSecOps practices as Scrum master, managing Jira workflows, sprint
						planning, backlog grooming, and progress reporting for cross-functional engineering team</label
					>
				</div>
				<div class="field-row">
					<input id="lm11" type="radio" name="lm-govcloud" disabled />
					<label for="lm11"
						>Designed comprehensive system architecture diagrams illustrating service components,
						data flows, network topology, and deployment patterns using Cameo Systems Modeler</label
					>
				</div>
				<div class="field-row">
					<input id="lm12" type="radio" name="lm-govcloud" disabled />
					<label for="lm12"
						>Provisioned EKS cluster in AWS GovCloud using Terraform and Helm charts, implementing
						IRSA for pod-level IAM roles, VPC CNI networking, and cluster autoscaler for secure,
						scalable data platform</label
					>
				</div>
			</div>
		</div>
	</div>
</div>

<style>
	.experience {
		font-size: 14px;
	}

	.job {
		margin-bottom: 16px;
	}

	.job-header h3 {
		margin: 0 0 12px 0;
		font-size: 16px;
	}

	.project {
		margin: 12px 0;
	}

	.project-title {
		font-style: italic;
		margin: 0 0 4px 0;
		font-size: 14px;
		text-align: left;
	}

	.field-row {
		margin: 4px 0;
		text-align: left;
	}

	.field-row label {
		font-size: 14px;
		text-align: left;
		font-family: 'Chicago';
	}

	.separator {
		margin: 16px 0;
	}
</style>
