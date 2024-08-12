## Contact
If you want to contact me, you can reach me at shubham22071@iiitd.ac.in

thanks

# Service Graph Visualization

This project is a dynamic Service Graph that visually represents the relationships between different services in a system. It displays services as nodes and their interactions as directed edges, providing a clear and interactive view of your service architecture.

## Features

- **Node Representation**: Each service is represented as a node with the service's name, port, Kubernetes namespace, and Kubernetes cluster.
- **Node Metrics**: Displays the total number of invocations for each service.
- **Error Visualization**: Uses a colored border around each node to indicate the success vs. error ratio. A fully red border indicates 100% errors, while a fully green border indicates 100% success.
- **Service Type Indication**: Includes a tiny icon on each node to indicate the type of service (HTTP, gRPC, MySQL, Redis, etc.).
- **Edge Representation**: The edges between nodes represent the relationships between services, where an edge from service A to service B indicates that service A calls service B.
- **Edge Metrics**: Shows the number of invocations between services through edge thickness.
- **Interactivity**: The graph is interactive, allowing users to drag nodes and explore service relationships.

## Technologies Used

- React.js for the frontend framework
- D3.js for the graph visualization

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed Node.js and npm (Node Package Manager)
- You have a basic understanding of React and JavaScript

## Installation

To install the Service Graph Visualization, follow these steps:

1. Clone the repository:
2. Navigate to the project directory:
3. Install the dependencies:


## Usage

To use the Service Graph Visualization, follow these steps:

1. Start the development server:
2. Open your web browser and visit `http://localhost:3000`

3. You should now see the Service Graph visualization with sample data.
