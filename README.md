# CleanStart Container for Java

Official Java container image optimized for enterprise environments. Includes the complete Java Development Kit (JDK) and Java Runtime Environment (JRE) for Java application development and deployment. Features security-hardened base image, minimal attack surface, and FIPS-compliant cryptographic modules. Supports both production deployments and development workflows with separate tagged versions. Includes Java runtime, development tools, and essential Java libraries.

## Key Features

- Complete Java development environment with JDK and JRE capabilities
- Optimized for cloud-native and microservices architectures

## Common Use Cases

- Building and deploying Java applications
- Cloud-native Java development

## Pull Commands

Download the runtime container images
```bash
docker pull ghcr.io/cleanstart-containers/jdk:latest
```
```bash
docker pull ghcr.io/cleanstart-containers/jdk:latest-dev
```

## Interactive Development

Start interactive session for development
```bash
docker run --rm -it --entrypoint /bin/sh ghcr.io/cleanstart-containers/jdk:latest-dev
```

## Container Start

Start the container
```bash
docker run --rm -it --name java-dev ghcr.io/cleanstart-containers/jdk:latest
```

## Best Practices

- Use specific image tags for production (avoid latest)
- Configure resource limits: memory and CPU constraints
- Enable read-only root filesystem when possible

## Architecture Support

### Multi-Platform Images
```bash
docker pull --platform linux/amd64 ghcr.io/cleanstart-containers/jdk:latest
```
```bash
docker pull --platform linux/arm64 ghcr.io/cleanstart-containers/jdk:latest
```

---

## Documentation Resources
Essential links and resources for further information
 
**CleanStart Images**: https://images.cleanstart.com/
 
**Community Images**:<br>
**Docker Hub**: https://hub.docker.com/u/cleanstart<br>
**GitHub**: https://github.com/cleanstart-containers<br>
**AWS ECR Public Gallery**: https://gallery.ecr.aws/cleanstart/
 
**Presence on Social Media**:<br>
**Community**: https://www.linkedin.com/groups/18324021/<br>
**YouTube**: https://www.youtube.com/@CleanStartOfficial<br>
 
**Contribute to Container Use Cases**: https://github.com/cleanstart-dev/cleanstart-use-cases/
