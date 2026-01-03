This repository serves as a project for deploying Umami analytics using Pergola. The core of this project is the `pergola.yaml` file, which acts as a Project Manifest.

A Project Manifest is a configuration file that defines the entire application stack, allowing it to be automatically built, deployed, and operated on the Pergola platform. In this specific repository, the `pergola.yaml` file details how Umami, a privacy-focused analytics platform, is containerized and configured for deployment through Pergola.

Essentially, this repository demonstrates how to use Pergola to manage and deploy an application like Umami, leveraging Pergola's capabilities for easy, non-intrusive, instant, and secure application delivery.

For more details on Pergola Project Manifests, refer to the [official documentation](https://docs.pergola.cloud/docs/reference/project-manifest).

# About Pergola

Pergola is an application delivery platform.

It provides developers an easy and non-intrusive way of building, deploying and operating their applications. And it enables their users and customers instant and secure access to these applications.

*   **Easy**, because you don't need to setup a server or to manually install your application on a remote VM. All you need is a working application, on your machine. Then you are just a few clicks away from deploying and serving your users.
*   **Non-intrusive**, because you don't need any special changes to your application to make it work on Pergola. Your code remains agnostic and can run anywhere. All additional configuration and setup happens on Pergola and remains on Pergola.
*   **Instant**, because once deployed on Pergola, your users can access your application immediately. There is no additional access or network configuration required. Simply share the link that Pergola has supplied for your application.
*   **Secure**, because you decide who can access your application and how, whether login is required, Single-Sign-On, with enforced Multi-Factor-Authentication or without. Restrict access to specific user groups or apply fine grained role-based rules. Regardless how far you push the security constraints, all communication to and from your application is always encrypted with state of the art cryptographic protocols.

![Pergola Architecture Overview](https://docs.pergola.cloud/assets/images/pergola_architecture_overview-902224413a2ab76018064265bd7154cf.png)


# About Umami

Umami is a simple, fast, privacy-focused alternative to Google Analytics. It provides you with the website metrics you care about in a user-friendly interface.

## Key Features:

*   **Analytics**: Collects essential metrics like page views, visitors, bounce rate, traffic sources, location, devices, and languages.
*   **Realtime Data**: Data is available in seconds, not days.
*   **Teams**: Securely share website access with different team members.
*   **Custom Events & Data**: Track specific actions and use custom properties for deeper analysis.
*   **UTM Tracking**: Measure campaign effectiveness with automatic UTM parameter collection.
*   **Sharing**: Easily share stats via secure, uniquely generated URLs.
*   **Insights**: Gain deep understanding of your website data with out-of-the-box insights, comparisons, breakdowns, funnels, retention, UTM tracking, goals, journey, and attribution.
*   **Privacy**: Private by default, GDPR & CCPA compliant, data anonymization, and no cookies required.
*   **Data Ownership**: You control your data, with options for self-hosting or exporting from Umami Cloud.
*   **Umami Cloud**: A fully managed, high-performance hosted solution with data import/export and email reports.

For more details, visit [umami.is/features](https://umami.is/features).
