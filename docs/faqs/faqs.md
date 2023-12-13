---
id: faqs
title: Frequently Asked Questions
sidebar_label: FAQs
slug: /faqs
---

These are some of the questions we are often asked about using Amplication

## What is Amplication?

Amplication is an open-source platform that helps developers build backend services without spending time on repetitive coding tasks and boilerplate code. Amplication auto-generates a fully functional, production-ready backend based on TypeScript and Node.js.

---

## How does Amplication work?

You just need to define your data models, roles, and permissions, and Amplication will generate a TypeScript Node.js application with everything you need already baked in. This includes fully functional REST API and GraphQL API for all your data models, authentication, role-based authorization, logging, and even an admin UI.

---

## Do I need to be an expert developer to work with Amplication?

Amplication is a great platform for professional developers, whatever their experience.
Even though beginners can get up-and-running quickly with Amplication, you own
the code and so can make full use of your code-writing talent to customize your
output and work your magic. Amplication is also a great solution for technical
leaders who seek to boost their teams' productivity and efficiency.

---

## How do I get started with Amplication?

You can generate your first service in minutes. These instructions will walk you through the steps of creating a service using our onboarding wizard.

[Create Your First Service](/first-service/)

---

## Is Amplication free?

Amplication was developed as an open-source software, and it is free for all to use. It is also offered for free on our managed service at [amplication.com](https://amplication.com) and has benefited dozens of thousands of users. Our commitment to open-source has allowed us to revolutionize how applications are developed, saving time and increasing productivity. Our pricing model is designed to build a sustainable business to enable Amplication to keep growing and to lead this revolution.

The pricing model enables teams working on small projects to continue to use the service for free. Teams working on larger projects can take advantage of one of the paid plans to enjoy advanced features.

See [Amplication’s licensing model](https://docs.amplication.com/about/about/licensing/)

---

## What is the difference between the Free and Enterprise Editions?

The Free edition is for individual developers or small teams focused on compact projects. It provides a robust foundation for backend service creation. It includes features like database and model management, role-based permissions, and both GraphQL & REST API support.

The Enterprise edition, on the other hand, is designed for large-scale organizational needs, emphasizing advanced security features, more git sync providers, and dedicated support, and includes single sign-on (SSO) to ensure a comprehensive environment for enterprise-level development.

To learn more about what's included with the Enterprise plan, see the **Premium Features** section of the docs.

## Who owns the code I generate with Amplication?

You own the code. Develop your service and applications however you wish, and deploy
it wherever you want; on the public cloud, private cloud, or on-premise.

---

## How can I get the code?

You can connect your project to your preferred git provider like [GitHub](/sync-with-github), [Bitbucket](/sync-with-bitbucket), or AWS CodeCommit.
After connecting to a git repo you can push a new Pull Request directly to a selected git repository. There is also a code-view option, that enables you to view the code in the console before you push it to your git provider.

---

## What server-side technologies does Amplication use?

NestJS, Prisma, PostgreSQL, MySQL, MongoDB, Passport, GraphQL, Swagger UI, Jest, Docker

---

## What client-side technologies does Amplication use?

Amplication focuses on creating the best backend. We provide the client only as a starting point for simple CRUD operations using the following technologies:
ReactJS, React-Admin, Axios, Formik.

Use your programming skills to build a great client.

---

## Is Amplication a no-code solution?

Amplication is a platform for professional developers, enabling you to automate
repetitive tasks, eliminating or reducing the time spent on repetitive server-side
tasks and boilerplate code. Your developer skills are very much required to create
your hand-crafted business logic, so it is definitely NOT a no-code solution. Amplication
reduces the amount of code you need to write, hence some may call it a low-code
solution for professional developers.

---

## What is the Amplication architecture?

Each Amplication project generates a server and admin UI, each in a separate folder:

- Server - for all the server components including REST API, GraphQL, Services and more.
- Admin - for the Admin UI including forms for CRUD operations on all data models.

---

## Can I customize the code generated by Amplication?

Definitely. The code is yours. Do with it what you wish. You can continuously customize
your code while continuing to get code from Amplication.

---

## Can I contribute to the development of Amplication?

We'd love to have you contribute! To find out how,read our [Contributing](https://docs.amplication.com/contributing/) guide.

---

## Can I work with GitLab (or other git providers) besides GitHub?

Amplication currently supports integration with [GitHub](/sync-with-github) (Free Plan), [Bitbucket](/sync-with-bitbucket) (Enterprise Plan), and AWS CodeCommit (Enterprise Plan).

We are planning to add support for more Git providers.
See our [Product Roadmap](https://docs.amplication.com/about/roadmap/).

---

## Which databases does Amplication support?

Amplication currently includes plugins to support PostgreSQL, MySQL, and MongoDB.
However, we generate apps that work with Prisma, so you could change the Prisma configuration to use other databases supported by Prisma.

---

## Which cloud platforms does Amplication support?

Amplication is shipped in container form and can be hosted on different cloud platforms like AWS, Heroku, Azure, Google Cloud Platform, Digital Ocean, and many more. 

Check out the following for more information:

1. [Deploy to Docker Desktop](https://docs.amplication.com/deploy/docker-desktop)
1. [Deploy to Kubernetes](https://docs.amplication.com/deploy/kubernetes)
2. [Deploying to Digital Ocean](https://dev.to/asiancat54x/deploying-amplication-app-to-digital-ocean-5d7k)

---

## Can I integrate Plugins into my Project?

Yes, Definitely. Some plugins are included in Amplication by default.
From the available list of plugins in amplication you can select any plugin you want for each of your services and install them.

Please follow this guide for more instructions on [Using plugins](https://docs.amplication.com/getting-started/getting-started/plugins/)

---

## What are the plugins supported by amplication that I can use?

The following plugins are currently available for your use. We are working on adding more plugins.

- MongoDB
- PostgreSQL DB
- MySQL DB
- Kafka
- Password JWT Authentication
- Password Basic Authentication
  Please ensure you arrange the order of installed plugins carefully, as the Amplication code is generated according to their order.

---

## Can I create my own Plugin(s) for my project?

Yes, Of Course.

To add more functionality, you can develop your own plugins as you require.
The Plugin architecture of amplication provides you the ecosystem to develop a plugin yourself.
Or you can also use plugins developed by the community, as they become available.

Keep an eye on our [Product Roadmap](https://docs.amplication.com/about/roadmap/).

---

## How does amplication help me to scale my Project?

Amplication incorporates the following practices to provide you with a platform to better scale your projects:

- Microservices support  
- Plugin system
- Monorepo with modular connected services  
- Custom sync flows and [smart git sync](/smart-git-sync) at the project level

With these new features and improvements in our new version, we make it much easier for you (or your team) to build scalable services, have better control over the generated code and collaborate with multiple developers to work on large scale solutions.

Read our documentation on [Amplication's key features](https://docs.amplication.com/#key-features-of-amplication) to learn more.

---

## What is monorepo? Does Amplication support it?

Amplication supports the monorepo model, allowing you and your team to collaborate on bigger projects.

In version control systems, a monorepo ("mono" meaning 'single' and "repo" is short for 'repository') is a software development strategy where code for many projects is stored in the same repository. Providing you the power to use the microservices approach for you services.

The monorepo model provides you with several advantages:
-Easy visibility of your services
-Code sharing among services to avoid code redundancy
-Improved collaboration
-Release management

---

## Will all my services be stored in the same or different repositories?

The choice is yours.
You can decide where you want to sync your code for each service.

You can store each service in its own separate repo.
You can also group services together in the same repository.

Amplication provides two options for organizing your generated code in a git repository:

- **Monorepo** - Stores your service code in a dedicated folder you select. Great if combining multiple services in one repo.
- **Polyrepo** - Puts your service code at the root of the repo. Better if you want a single service per repository.

:::note
Check out our docs for more on syncing to a git repository and how Amplication handles pull requests:

- [Sync with GitHub](/sync-with-github)
- [Sync with Bitbucket](/sync-with-bitbucket)
:::

---

## What is Microservices architecture?

Microservices (or microservices architecture) is a cloud native architectural approach in which a single application is composed of many loosely coupled and independently deployable smaller components, or services.

Want more information? [Read this](https://amplication.com/blog/an-introduction-to-microservices).

---

## How does the microservices architecture benefit my development?

Amplication's Microservices architecture enables you to develop services with ease and select the best tech stack for each service. Different development teams can work on different services without cross-team dependencies.

Project development becomes easier with the following functionalities:
-You can connect to a single git repo at the project level saving a lot of your time that would be spent manually connecting the services
-You can make a single commit at the project level

Learn more about the benefits on our [Support for Microservices Architecture](https://amplication.com/blog/release-0150-support-for-microservices-architecture) blog post.

---

## How are microservices incorporated in Amplication?

Amplication supports microservices through the Project hierarchy. A Project groups together multiple resources used and created by Amplication, enabling support for multiple use cases. This simplifies the creation of connected Services, and makes it much easier to [sync with your preferred git provider](/smart-git-sync/) across multiple Services.

---

## What is Project, Resources and Services structure in Amplication?

This structure helps you to manage various services (architected as microservices) and the resources associated with each service.

It provides a much simple and easy-to-maintain project flow with multiple services.

Read more about the hierarchy [here](https://docs.amplication.com/projects-resources-services/).

---

## How do I keep track of my codebase if it involves continuous development?

Amplication comes with version control built-in enabling you to see the changes made in the services and push the code to your preferred git provider.
We call this feature [Smart Git Sync](/smart-git-sync/).
In Amplication, your work is auto saved but not committed, thus giving you the opportunity to review.
All the pending changes are visible under 'Pending Changes', ready for you to review and commit.

Read [How To Commit Changes](https://docs.amplication.com/how-to/commit-changes/).

---

## What is Message Broker?

Message Broker enables your microservices to communicate with each other.
A message broker is software that enables applications, systems, and services to communicate with each other and exchange information. This allows interdependent services to “talk” with one another directly, even if they were written in different languages or implemented on different platforms.
Amplication provides a plugin for Kafka Message Broker that can be installed as required.
Follow the [Instructions](https://docs.amplication.com/getting-started/getting-started/plugins/)

To create a Message Broker follow the [How to Create a Message Broker Instruction](https://docs.amplication.com/how-to/create-message-broker/)

---

## What is Phone Home in Amplication?

A software that allows the amplication core team to see the number of amplication deployments made by the users of amplication.
This information is used to better understand the usage of amplication platform by users and how to improve the platform with enhanced or new features.

---

## For any issue related to Amplication development where can I get answers?

You can look into the [docs](https://docs.amplication.com/) under [_Troubleshooting_](/errors/) that have answers for a number of Issues relating to Set-up, Code Generation, Database, Authorization, and Git Sync.
If it's a new issue you can ask in the community or raise an issue yourself in GitHub.

Read the guidelines to contribute [here](https://docs.amplication.com/contributing/).

---

## How can I keep in touch with the Amplication community?

Join us at any of the following locations:

- [GitHub](https://github.com/amplication)
- [Discord](https://amplication.com/discord)
- [Amplication website](https://amplication.com/)
- [Blog](https://amplication.com/blog)
- [Docs](https://docs.amplication.com/getting-started/)

---
