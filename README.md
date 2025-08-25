Overview
This dataset contains four representative server topology configurations designed for evaluating distributed multimodal generative model orchestration systems. The datasets simulate real-world distributed computing infrastructures with distinct geographical characteristics and network scales, specifically designed for reinforcement learning-based resource optimization research.
Dataset Description

Server Topologies
The dataset includes four main server topology configurations (S1-S4) that represent different scales and deployment scenarios:
S1 - Switzerland Region (Small-scale High-density)

Nodes: 25 distributed server nodes
Computational Capacity: 16-54 units (average: 34.6 units)
Storage Capacity: 16-34 units (average: 25.3 units)
Network Topology: Sparse connection with average connectivity degree of 3.2
Deployment Type: Regional data center deployment
Use Case: Small-scale high-density deployment evaluation

S2 - United Kingdom Region (Medium-scale Distributed)

Nodes: 51 distributed server nodes
Computational Capacity: 16-53 units (average: 35.8 units)
Storage Capacity: 15-38 units (average: 26.2 units)
Deployment Type: National-scale infrastructure
Use Case: Medium-scale geographically distributed deployment

S3 - Germany Region (Large-scale Heterogeneous)

Nodes: 101 distributed server nodes
Computational Capacity: 19-55 units (average: 36.7 units)
Storage Capacity: 12-39 units (average: 26.0 units)
Deployment Type: Large-scale heterogeneous resource environment
Use Case: Complexity validation for large-scale deployments

S4 - Milan City Network (Urban Edge Computing)

Nodes: 31 densely deployed servers
Deployment Type: Urban edge computing scenario
Use Case: Edge intelligence in smart cities evaluation

Model Deployment
Each topology contains a comprehensive set of generative models distributed across nodes:

Total Models: 227 generative models per topology
Text-to-Text Models: 191 models
Text-to-Image Models: 30 models
Image-to-Video Models: 6 models

Note: Distribution strategies differ across topologies to reflect realistic heterogeneous deployment scenarios.
Task Datasets
Training and Testing Split

Training Set: 1,000 user tasks per topology
Test Set: 200 independent tasks per topology
Special Configuration: S4 serves exclusively as a test set for cross-domain generalization evaluation
