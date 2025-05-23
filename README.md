# SIT737-2024-T1-Prac10P - Node Monitoring App Deployment on GCP Kubernetes

## Overview

This project demonstrates how to containerize a simple Node.js monitoring application, deploy it to a Kubernetes cluster on Google Cloud Platform (GCP), and implement monitoring and visibility using Google Cloud Monitoring (formerly Stackdriver).

## Features

- Dockerized Node.js application
- Kubernetes deployment via `kubectl`
- Hosted on GCP GKE (Autopilot or Standard cluster)
- Monitoring and logging via Google Cloud Monitoring and Logging
- LoadBalancer service for external access

---

## Application

This app is a simple Node.js-based server that collects or exposes monitoring data. The image is hosted on Docker Hub:
