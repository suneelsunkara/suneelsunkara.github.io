---
layout: post
title: "AKS-Checklist: Development"
date: 2021-03-15
---

| Consideration | Description | Comment |
| --- | --- | --- |
| `Implement a proper Liveness probe` | Many applications running for long periods of time eventually transition to broken states, and cannot recover except by being restarted. Kubernetes provides liveness probes to detect and remedy such situations. The probe is here to tell Kubernetes to restart your pod when it is not responding anymore! | Ref 1: https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-probes/ Ref 2: https://docs.microsoft.com/en-us/azure/application-gateway/ingress-controller-add-health-probes#with-readinessprobe-or-livenessprobe  |
