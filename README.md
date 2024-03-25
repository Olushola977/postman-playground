# API Testing with Tag-Based Execution in Postman

## Overview
This repository contains scripts and instructions for enhancing API testing efficiency using tag-based execution in Postman. By leveraging tags within your Postman collections, you can selectively run tests based on specific criteria, streamlining your testing workflows and improving organization.

## Getting Started
To get started with tag-based execution in Postman, follow these steps:

1. Download the collection and environment json files in workflow directory.

2. **Import the Collection**: Import the provided Postman collection file (`Tag-Testing.postman_collection`) into your Postman workspace.

3. **Set Up Environment Variables**: Import the provided environment and configure the environment variables within Postman to define your testing criteria. Specifically, set the `tags` variable to specify the tags you want to use for test execution.

4. **Integrate Scripts**: Replace the collection-id in the collection variable and the postman-api-key in the environment variable with your ID and KEY.

5. **Execute Tests**: Run the collection in Postman and observe how requests are selectively executed based on the defined tags.

## Script Overview
The repository includes the following scripts:

- `pre-request script`: Determines the next request to be executed before sending the current request.
- `test script (initial request)`: Populates the list of requests to be executed initially based on specified tags.
- `test script (other requests)`: Determines the next request to be executed after the current request completes.

## Contributing
Contributions are welcome! If you have ideas for improvements or new features, feel free to submit a pull request.

Happy hacking 🎉
