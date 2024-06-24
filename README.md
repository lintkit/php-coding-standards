# LintKit: PHP Coding Standards Kit

A preconfigured [PHP Coding Standards](https://github.com/PHP-CS-Fixer/PHP-CS-Fixer) kit implementation.

## Usage

### GitLab

```yaml
# Lint the PHP
.php:coding-standards:
  image: ghcr.io/lintkit/php-coding-standards-kit:latest
  script:
    - /lintkit
```

### GitHub

```yaml
- name: Lint PHP
  uses: lintkit/php-coding-standard-kit@v1
```

### Local

```bash
docker pull ghcr.io/lintkit/php-coding-standards-kit:latest
docker run -it --rm -v $(pwd):/app ghcr.io/lintkit/php-coding-standards-kit
```
