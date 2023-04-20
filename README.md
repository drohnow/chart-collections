# helm-apps

This repo contains a collection of helm charts that are derived from the [replicated library chart](https://github.com/replicatedhq/helm-charts).

1. Kubevader (aka Kubeinvader) - invader game
   - single deployment; very simple application
   - external access: NodePort
   - replicated library 0.5.2
   
2. GarageRSVP - A 2-tier app; web application that is backed by a mongodb
   - multiple deployments:
     - web frontend
     - mongodb
   - external access: Ingress
   - Replicated Library 0.5.2
