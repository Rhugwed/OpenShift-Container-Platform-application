# OpenShift-Container-Platform-application
Creating an OpenShift Container Platform application from components that include source or binary code, images, and templates by using the OpenShift Container Platform CLI.
Creating an application from source code
With the new-app command you can create applications from source code in a local or remote Git repository.

The new-app command creates a build configuration, which itself creates a new application image from your source code. The new-app command typically also creates a deployment configuration to deploy the new image, and a service to provide load-balanced access to the deployment running your image.

OpenShift Container Platform automatically detects whether the Pipeline or Source build strategy should be used, and in the case of Source builds, detects an appropriate language builder image.
