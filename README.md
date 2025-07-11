# Apache Fluss Website

This repository hosts the content for the **Apache Fluss website** at [https://fluss.apache.org](https://fluss.apache.org). The static HTML content for the site is published in the `asf-site` branch.

The website source code is maintained in the [`website/`](https://github.com/apache/fluss/tree/main/website) directory of the [apache/fluss](https://github.com/apache/fluss) repository. Different versions of the documentation are maintained in separate branches of the `apache/fluss` repository. For example: the `release-0.7` branch contains the documentation for version v0.7.
  
The `main` branch of this repository (`apache/fluss-website`) contains a GitHub Actions workflow that **automatically builds and deploys** the website and documentation whenever changes are made to the `main` or `release-*` branches of the `apache/fluss` repository under its `website/` directory.

For more information on contributing documentation, see:  
[How to Contribute Documentation](https://fluss.apache.org/community/how-to-contribute/contribute-docs/)
