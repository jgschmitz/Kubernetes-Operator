# Deploying a MongoDB Replica Set with MongoDB Kubernetes Operator

This guide outlines the steps to deploy a MongoDB replica set using the MongoDB Kubernetes Operator. The MongoDB Kubernetes Operator simplifies the deployment and management of MongoDB clusters on Kubernetes.

## Prerequisites

Before proceeding with the deployment, ensure that you have the following prerequisites:

- Kubernetes cluster up and running
- `kubectl` command-line tool installed and configured
- MongoDB Kubernetes Operator installed in your cluster

## Steps

### Step 1: Create a Namespace

Create a Kubernetes namespace to isolate the MongoDB resources:

```shell
kubectl create namespace my-mongodb
