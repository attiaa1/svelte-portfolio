<div class="skills-grid" style="overflow: none; justify-content: center;">
	<div class="skill-category">
		<h3>Languages</h3>
		<div class="field-row">
			<input id="shell" type="checkbox" checked disabled />
			<label for="shell">Shell</label>
		</div>
		<div class="field-row">
			<input id="python" type="checkbox" checked disabled />
			<label for="python">Python</label>
		</div>
		<div class="field-row">
			<input id="java" type="checkbox" checked disabled />
			<label for="java">Java</label>
		</div>
		<div class="field-row">
			<input id="golang" type="checkbox" checked disabled />
			<label for="golang">Golang</label>
		</div>
		<div class="field-row">
			<input id="rust" type="checkbox" checked disabled />
			<label for="rust">Rust</label>
		</div>
		<div class="field-row">
			<input id="typescript" type="checkbox" checked disabled />
			<label for="typescript">Typescript</label>
		</div>
	</div>

	<div class="skill-category">
		<h3>Cloud</h3>
		<div class="field-row">
			<input id="aws" type="checkbox" checked disabled />
			<label for="aws">AWS</label>
		</div>
		<div class="field-row">
			<input id="azure" type="checkbox" checked disabled />
			<label for="azure">Azure</label>
		</div>
		<div class="field-row">
			<input id="kubernetes" type="checkbox" checked disabled />
			<label for="kubernetes">Kubernetes</label>
		</div>
		<div class="field-row">
			<input id="docker" type="checkbox" checked disabled />
			<label for="docker">Docker</label>
		</div>
		<div class="field-row">
			<input id="terraform" type="checkbox" checked disabled />
			<label for="terraform">Terraform</label>
		</div>
		<div class="field-row">
			<input id="helm" type="checkbox" checked disabled />
			<label for="helm">Helm</label>
		</div>
	</div>

	<div class="skill-category">
		<h3>Data</h3>
		<div class="field-row">
			<input id="kafka" type="checkbox" checked disabled />
			<label for="kafka">Kafka</label>
		</div>
		<div class="field-row">
			<input id="prometheus" type="checkbox" checked disabled />
			<label for="prometheus">Prometheus</label>
		</div>
		<div class="field-row">
			<input id="grafana" type="checkbox" checked disabled />
			<label for="grafana">Grafana</label>
		</div>
		<div class="field-row">
			<input id="crowdstrike" type="checkbox" checked disabled />
			<label for="crowdstrike">Crowdstrike</label>
		</div>
		<div class="field-row">
			<input id="dynamodb" type="checkbox" checked disabled />
			<label for="dynamodb">DynamoDB</label>
		</div>
		<div class="field-row">
			<input id="postgresql" type="checkbox" checked disabled />
			<label for="postgresql">PostgreSQL</label>
		</div>
	</div>
</div>

<style>
	.skills-grid {
		display: grid;
		grid-template-columns: repeat(3, 1fr);
		gap: 20px;
	}

	.skill-category {
		width: 25vw;
	}

	.skill-category h3 {
		font-size: 14px;
		margin-bottom: 8px;
		border-bottom: 1px solid #000;
		padding-bottom: 4px;
		text-align: center;
	}

	.field-row {
		font-size: 14;
		font-family: Chicago;
	}
</style>
