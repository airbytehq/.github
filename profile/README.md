<p align="center">
  <a href="https://airbyte.com"><img src="https://assets.website-files.com/605e01bc25f7e19a82e74788/624d9c4a375a55100be6b257_Airbyte_logo_color_dark.svg" alt="Airbyte"></a>
</p>
<p align="center">
    <b>Data integration platform for ELT pipelines from APIs, databases & files to databases, warehouses & lakes</b>
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
Airbyte is an open-source data movement infrastructure for building extract and load (EL) data pipelines. It is designed for versatility, scalability, and ease-of-use.

There are three major components to know in Airbyte:

The connector catalog
- 350+ pre-built connectors: Airbyte’s connector catalog comes “out-of-the-box” with over 350 pre-built connectors. These connectors can be used to start replicating data from a source to a destination in just a few minutes.
- No-Code Connector Builder: You can easily extend Airbyte’s functionality to support your custom use cases through tools like the [No-Code Connector Builder](https://docs.airbyte.com/connector-development/connector-builder-ui/overview).
- The platform: Airbyte’s platform provides all the horizontal services required to configure and scale data movement operations, available as [cloud-managed](https://airbyte.com/product/airbyte-cloud) or [self-managed](https://airbyte.com/product/airbyte-enterprise).
- The user interface: Airbyte features a UI, [PyAirbyte](https://docs.airbyte.com/using-airbyte/pyairbyte/getting-started) (Python library), [API](https://docs.airbyte.com/api-documentation), and [Terraform Provider](https://docs.airbyte.com/terraform-documentation) to integrate with your preferred tooling and approach to infrastructure management.
Airbyte is suitable for a wide range of data integration use cases, including AI data infrastructure and EL(T) workloads. Airbyte is also [embeddable](https://airbyte.com/product/powered-by-airbyte) within your own application or platform to power your product.

Products:

- [`Airbyte Cloud`](https://cloud.airbyte.com) - A hosted service that allows you to focus on moving data while we take care of managing the infrastructure
- [`Airbyte Enterprise`](https://docs.airbyte.com/enterprise-setup/) - run Airbyte in own your infrastructure with access to Enterprise feature and special support.
- [`Airbyte Open-Source`](https://docs.airbyte.com/using-airbyte/getting-started/#self-managed-community-oss) - run Airbyte in own infra and have full control over your data.

Main Repositories:

- [`Airbyte`](https://github.com/airbytehq/airbyte) - all Airbyte connectors Python and Java, Airbyte CDK and Airbyte CI tools.
- [`abctl`](https://github.com/airbytehq/abctl) - CI tool to deploy Airbyte anywhere anytime.
- [`Airbyte Platform`](https://github.com/airbytehq/airbyte-platform) - the core platform and Helm Charts.
- [`Airbyte Protocol`](https://github.com/airbytehq/airbyte-protocol) - describes a series of standard components and all the interactions between them in order to declare an ELT pipeline.

Extensions:

- [`Terraform`](https://github.com/airbytehq/terraform-provider-airbyte) - declares and have code versioned Airbyte Connectors as code.
- [`Helm Charts`](https://artifacthub.io/packages/helm/airbyte/airbyte) - run Airbyte on Kubernetes.
- [`PyAirbyte`](https://github.com/airbytehq/PyAirbyte) - use Airbyte connectors directly in Python without the Airbyte Platform.
- [`Airbyte API Python SDK`](https://github.com/airbytehq/airbyte-api-python-sdk) - control the Airbyte Platform using Python.
- [`Airbyte API Java SDK`](https://github.com/airbytehq/airbyte-api-java-sdk) - control the Airbyte Platform using Java.

## Learn more

| Section | Description |
|-|-|
| [Company Website](https://airbyte.com) | Airbyte product and company info |
| [Airbyte Documentation](https://docs.airbyte.com/) | Get started laerning Airbyte concepts and tutorials |
