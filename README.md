# toolarium-icap-calmav-docker

Docker project to build an ICAP-Server based on CalmAV.

## Build

Prerequisites: [cb](https://github.com/toolarium/common-build) must be installed.

```bash
cb dockerBuild
```

## Deploy to Docker Hub

1. Log in to Docker Hub:
   ```bash
   docker login
   ```

2. Push the image:
   ```bash
   cb dockerPush
   ```

The image name and organization can be configured in `gradle.properties`:
```properties
dockerRegistry      = docker.io
dockerOrganization  = <your-dockerhub-username>
```

## Built With

* [cb](https://github.com/toolarium/common-build) - The toolarium common build

## License

This project is licensed under the MIT License: https://mit-license.org - see the [LICENSE](LICENSE) file for details
