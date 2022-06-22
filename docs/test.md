# Introduction

This reference architecture details a hub-spoke topology in Azure. The hub virtual network acts as a central point of connectivity to many spoke virtual networks. The hub can also be used as the connectivity point to your on-premises networks. The spoke virtual networks peer with the hub and can be used to isolate workloads.

The benefits of using a hub and spoke configuration include cost savings, overcoming subscription limits, and workload isolation.

## Network Design
