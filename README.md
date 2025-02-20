# kernelci-nipa

**kernelci-nipa** is designed to bridge KernelCI's [Maestro](https://github.com/kernelci/kernelci-pipeline) with the [Netdev CI system](https://github.com/linux-netdev/nipa/wiki/Netdev-CI-system). These scripts facilitate the extraction and transformation of KernelCI test results into a JSONs files specified by the Netdev CI system, enabling seamless data consumption by [NIPA](https://github.com/linux-netdev/nipa).


## Prerequisites

Before using kernelci-nipa, ensure the following are installed:

- Python 3.x
- Required Python packages listed in `requirements.txt`

Install the necessary packages using:

```bash
pip install -r requirements.txt
```

## Usage

To generate a JSON report for a specific KernelCI job, execute:

```bash
results --id <job_id>
```

Replace <job_id> with the actual job identifier from KernelCI.