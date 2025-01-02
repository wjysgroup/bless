# bless


## Detailed Description
Shadow is a self-developed Android plugin framework by Tencent, tested by hundreds of millions of users online. Shadow not only shares the key code of the plugin technology but also shares all the designs needed for online deployment.

### Purpose
The purpose of this repository is to provide a robust and efficient Android plugin framework that can be easily integrated into existing projects.

### Features
- Reuse of independent installation App source code: The source code of the plugin App can be normally installed and run.
- Zero reflection and no Hack implementation of plugin technology: It is theoretically determined that there is no need to develop compatibility for any system, and there is no hidden API call, which does not conflict with Google's strategy of restricting access to non-public SDK interfaces.
- Fully dynamic plugin framework: It is difficult to achieve a perfect plugin framework at one time, but Shadow makes these implementations fully dynamic, making the code of the plugin framework a part of the plugin. The iteration of the plugin is no longer limited by the old version of the plugin framework packaged by the host.
- Minimal host increment: Thanks to the fully dynamic implementation, the actual code integrated into the host program is minimal (about 15KB, 160 methods).
- Kotlin implementation: The core code of core.loader and core.transform is completely implemented in Kotlin, making the code concise and easy to maintain.

### Usage Instructions
To use this repository, follow the instructions below:
1. Clone the repository to your local machine.
2. Follow the setup instructions in the documentation to integrate the plugin framework into your project.
3. Build and run your project to see the plugin framework in action.

## Contributing
We welcome contributions to this repository. To contribute, follow these steps:
1. Fork the repository to your own GitHub account.
2. Create a new branch for your changes.
3. Make your changes and commit them with a clear and concise message.
4. Push your changes to your forked repository.
5. Create a pull request to the main repository with a description of your changes.

## Reporting Issues and Requesting Features
If you encounter any issues or have any feature requests, please follow these steps:
1. Check the existing issues to see if your issue or request has already been reported.
2. If not, create a new issue with a clear and concise description of the problem or request.
3. Provide any relevant information, such as steps to reproduce the issue or examples of the requested feature.
4. We will review your issue or request and respond as soon as possible.
