# Brender Studio
Brender Studio is a cross-platform desktop application (macOS, Linux, and Windows) that enables users to connect to AWS services for rendering Blender 3D scenes in the cloud. It is an open-source application, and users are responsible for associated expenses; in other words, there are no intermediaries, and they only pay for what they use.

## How does it work?
Brender Studio primarily utilizes AWS CLI for resource creation and communication with AWS services through a graphical interface. Internally, Brender Studio utilizes predefined templates (CloudFormation/CDK) with AWS services such as storage, server logic, Docker images, etc. The application primarily facilitates resource creation and deployment without the need for programming.