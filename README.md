# My-Apps

This repository provides a convenient structure for deploying applications on cluster.

## Project Structure

- Each application is located under the `apps` directory.
- Each application's Kubernetes objects are deployed by pointing to its respective directory containing the YAML files.

### Example:
For an application named `nginx`, the YAML files should be placed in: nginx-app
