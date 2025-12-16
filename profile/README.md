<p align="center">
  <a href="https://airbyte.com"><img src="https://assets.website-files.com/605e01bc25f7e19a82e74788/624d9c4a375a55100be6b257_Airbyte_logo_color_dark.svg" alt="Airbyte"></a>
</p>
<p align="center">
    <b>A comprehensive data infrastructure for replication and AI agents</b>
</p>
<p align="center">

<a href="https://github.com/airbytehq/airbyte/stargazers/" target="_blank">
    <img src="https://img.shields.io/github/stars/airbytehq/airbyte?style=social&label=Star&maxAge=2592000" alt="Test">
</a>

<a href="https://x.com/AirbyteHQ" target="_blank">
    <img alt="X" src="https://img.shields.io/twitter/follow/Airbyte.svg?style=social&label=Follow">
</a>

<a href="https://www.youtube.com/c/AirbyteHQ/?sub_confirmation=1" target="_blank">
    <img alt="YouTube Channel Views" src="https://img.shields.io/youtube/channel/views/UCQ_JWEFzs1_INqdhIO3kmrw?style=social">
</a>

<a href="https://airbytehq.slack.com/" target="_blank">
    <img src="https://img.shields.io/badge/slack-join-white.svg?logo=slack" alt="Slack">
</a>

</p>
Airbyte is open-source data infrastructure that helps teams move data reliably and give AI agents real-time access to context. Whether you're replicating databases into warehouses for analytics or building agentic applications that need live context from SaaS APIs, Airbyte provides a consistent way to access and move data across systems, backed by a large open-source community and an ever growing ecosystem of connectors. 

### What Airbyte Offers
#### 1. Agent Connectors 
As teams build AI applications and agentic workflows, they need reliable access to real-time context across systems. Airbyte offers a growing set of agent-native connectors: standalone Python SDKs designed for real-time fetch and search operations, with write and trigger operations coming soon. These connectors provide:
- 10+ agent connectors available as individual Python SDKs (releasing new connectors weekly)
- Strongly-typed, well-documented access to third-party APIs
- Real-time read access to systems like Salesforce, HubSpot, GitHub, Jira, Stripe, Zendesk, Gong, and more
- MCP interface compatible with modern agent platforms
- Built on PydanticAI and compatible with LangChain, LlamaIndex, and other AI libraries. PydanticAI, LangChain, LlamaIndex) and MCP standard

#### 2. Data Replication
Airbyte provides the infrastructure for building extract-and-load pipelines from APIs, databases, and files into databases, warehouses, and lakes. It is designed for versatility, scalability, and ease of use.
The replication connector catalog includes:
- 600+ pre-built replication and agent connectors: Airbyte’s connector catalog comes “out-of-the-box” with over 600 connectors. These connectors can be used to start replicating data from a source to a destination in just a few minutes.
- No-Code Connector Builder: You can easily extend Airbyte’s functionality to support your custom use cases through tools like the [No-Code Connector Builder](https://docs.airbyte.com/connector-development/connector-builder-ui/overview).
- The platform: Airbyte’s platform provides all the horizontal services required to configure and scale data movement operations, available as [cloud-managed](https://airbyte.com/product/airbyte-cloud) or open source self-managed.
- The user interface: Airbyte features a UI, [PyAirbyte](https://docs.airbyte.com/using-airbyte/pyairbyte/getting-started) (Python library), [API](https://docs.airbyte.com/api-documentation), and [Terraform Provider](https://docs.airbyte.com/terraform-documentation) to integrate with your preferred tooling and approach to infrastructure management.
Airbyte is suitable for a wide range of data integration use cases, including AI data infrastructure and EL(T) workloads. Airbyte is also [embeddable](https://airbyte.com/product/powered-by-airbyte) within your own application or platform to power your product.

This foundation is battle-tested in production across thousands of companies and supported by a community of over 27,000 developers.

### Products:

- [`Airbyte Cloud`](https://cloud.airbyte.com) - A hosted service that allows you to focus on moving data while we take care of managing the infrastructure
- [`Airbyte Open-Source`](https://docs.airbyte.com/using-airbyte/getting-started/) - Deploy on your own infrastructure and start moving data 
- [`Airbyte Embedded`](https://docs.airbyte.com/ai-agents/embedded/) -  Airbyte Embedded enables you to add hundreds of data integrations into your product, allowing end-users to authenticate their sources and sync data to your warehouse 

### Main Repositories:
Highlighted below are the main repositories. We accept community contributions to the [`Airbyte`](https://github.com/airbytehq/airbyte) repo.

- [`airbyte-agent-connectors`](https://github.com/airbytehq/airbyte-ai-connectors) - Python SDKs for use in your app, an agent framework, or MCP
- [`Airbyte`](https://github.com/airbytehq/airbyte) - all Airbyte replication connectors, Airbyte CDK and Airbyte CI tools
- [`abctl`](https://github.com/airbytehq/abctl) -  Command line tool to deploy Airbyte locally or to any single node physical or virtual machine
- [`Airbyte Platform`](https://github.com/airbytehq/airbyte-platform) - the data replication platform
- [`Airbyte Protocol`](https://github.com/airbytehq/airbyte-protocol) - describes a series of standard components and all the interactions between them in order to declare an ELT pipeline

### Extensions:

- [`Terraform`](https://github.com/airbytehq/terraform-provider-airbyte) - declaratively version Airbyte Connectors as code.
- [`Helm Charts`](https://artifacthub.io/packages/helm/airbyte/airbyte) - run Airbyte at scale on Kubernetes.
- [`pyAirbyte`](https://github.com/airbytehq/PyAirbyte) - use Airbyte connectors directly in Python without the Airbyte Platform.
- [`Airbyte REST API`](http://reference.airbyte.com) - Programmatically control Airbyte Cloud through an API.

### Learn more

| Section | Description |
|-|-|
| [Company Website](https://airbyte.com) | Airbyte product and company information |
| [Airbyte Documentation](https://docs.airbyte.com/) | Learn how to get started, Airbyte concepts, and our features |
