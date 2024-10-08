# Introduction

## What is Kamal?

Kamal is an open-source deployment tool developed by Basecamp. It's designed to simplify the process of deploying web applications to servers or cloud environments. Kamal leverages Docker containers and uses SSH for server communication, providing a streamlined approach to application deployment without the complexity of traditional container orchestration systems like Kubernetes.

Key features of Kamal include:
- Zero-downtime deployments
- Simple configuration using YAML files
- Support for multiple environments and servers
- Built-in rolling updates and rollbacks
- Integration with Docker registries

## Why use Kamal for deployments?

Kamal offers several advantages that make it an attractive choice for developers and teams:

1. **Simplicity**: Kamal provides a straightforward way to deploy applications without the steep learning curve associated with more complex systems.

2. **Flexibility**: It works with any Dockerized application, giving you the freedom to use your preferred tech stack.

3. **Cost-effective**: Kamal can deploy to basic VPS instances, potentially reducing infrastructure costs compared to managed container services.

4. **Zero-downtime deployments**: Kamal ensures your application remains available during updates, minimizing disruption to users.

5. **Easy rollbacks**: If something goes wrong, Kamal makes it simple to revert to a previous version of your application.

6. **Scalability**: While simple to use for single-server deployments, Kamal can also handle multi-server setups as your application grows.

## Prerequisites

Before diving into Kamal, ensure you have the following:

1. **Ruby**: Kamal is written in Ruby and requires Ruby 2.7 or later. You can check your Ruby version with:
   ```bash
   ruby --version
   ```

2. **Docker**: Kamal uses Docker to containerize and deploy applications. Install Docker on your local machine and ensure it's running. Verify with:
   ```bash
   docker --version
   ```

3. **Basic command-line knowledge**: You should be comfortable using the terminal or command prompt, as Kamal is primarily used through command-line interfaces.

4. **SSH access**: Familiarity with SSH is beneficial, as Kamal uses SSH to communicate with servers.

5. **Git**: While not strictly required for Kamal, Git is commonly used in development workflows. Install Git and verify with:
   ```bash
   git --version
   ```

6. **A web application**: To follow along with deployment examples, you'll need a web application. If you don't have one, we'll create a simple one in the next chapter.

With these prerequisites in place, you're ready to start your journey with Kamal, from understanding its basic concepts to mastering advanced deployment strategies.