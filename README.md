# ComfyUI-FastAPI

:warning: Work still in progress :warning:

This project enhances [ComfyUI](https://github.com/comfyanonymous/ComfyUI), by adding a feature that allows users to generate [FastAPI](https://fastapi.tiangolo.com/) source code directly from their ComfyUI workflows. This new feature simplifies the deployment of image generation workflows as web APIs, making it easier to integrate AI models into various applications.

# Features

- **User-Friendly Interface**: Select input arguments and specify endpoint names directly within the ComfyUI interface.
- **Automatic Code Generation**: Generate FastAPI code that handles input arguments and outputs based on the exported workflow JSON.
- **Seamless Integration**: Export workflows as JSON files and automatically generate the corresponding FastAPI code.

# Usage

1. **Run ComfyUI**:
    - Start ComfyUI and load your workflow.

2. **Select Input Arguments**:
    - Use the enhanced ComfyUI interface to select the expected input arguments and specify the endpoint name.

3. **Generate FastAPI Code**:
    - Press the "Generate API" button. The workflow will be exported as a JSON file, and the corresponding FastAPI code will be generated.

4. **Deploy the FastAPI Application**:
    - Run the generated FastAPI application.

# :star: Star Us!
If you find this project useful, please consider giving it a star on GitHub. This helps the project to gain visibility and encourages more contributors to join in. Thank you for your support!

# Contribute
Thanks for your interest in contributing to the source code! We welcome help from anyone and appreciate every contribution, no matter how small!

If you're ready to contribute, please create a fork, make your changes on a new branch, commit them, and then submit a pull request for review. We'll consider it for integration into the main code base.

# Credits
- [ComfyUI](https://github.com/comfyanonymous/ComfyUI)
