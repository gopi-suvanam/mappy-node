# Mappy

Mappy is a decentralized, distributed computing framework designed for web-scale operations. It allows community-driven computation by distributing tasks to web workers across the internet. The framework efficiently maps code to various workers, enabling large-scale distributed computing in a decentralized manner.

## Features

- **Decentralized Task Distribution**: Mappy nodes distribute computation jobs to available web workers.
- **Community Computation**: Harness the power of community-driven processing for large-scale tasks.
- **Scalable and Flexible**: Suitable for various computational needs and scales seamlessly.
- **Easy Integration**: Simple to set up and integrate into existing systems.

## How It Works

1. **Job Submission**: The original compute requester submits a job to the Mappy node.
2. **Job Distribution**: The Mappy node exposes the job to the network of web workers.
3. **Job Processing**: Web workers from the community pick up jobs, process them, and return the results to the node.
4. **Result Collation**: The Mappy node collates the processed results and delivers them back to the original compute requester.

## Installation

To get started with Mappy, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/gopi-suvanam/mappy-node.git
   cd mappy
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Start the Node**:
   ```bash
   npm start
   ```

## Usage

### Submitting a Job

To submit a job to the Mappy node, use the following API endpoint:

```http
POST /
Content-Type: application/json

{
  "func": <code for the function to run">,
  "args": <list of arguments>
}
```





## Contributing

We welcome contributions from the community! 

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/gopi-suvanam/mappy-node/blob/master/LICENSE) file for details.

## Contact

For questions or suggestions, please open an issue on GitHub.

