# Dockerを自動インストールするUserData

```
#!/bin/bash
curl -fsSL https://test.docker.com -o test-docker.sh
sh test-docker.sh
groupadd docker
usermod -aG docker ubuntu
```

