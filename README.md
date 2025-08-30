# Cursor Rules for DDD Projects

This repository stores generic [Cursor](https://cursor.sh/) rules, primarily intended for use with Domain-Driven Design (DDD) projects.

## Purpose

The main goal is to maintain a central place for common Cursor configurations and rules that can be easily reused across multiple personal DDD projects. This avoids duplication and makes managing updates simpler.

## Usage

To use these rules in another project, create a symbolic link (soft link) from this repository to your target project directory.

For example, if you have a specific rule file named `generic-ddd-rule.yaml` in this repository, you can link it into your project like this:

```bash
# Replace /path/to/cursor-rules with the actual path to this repository
# Replace /path/to/your-ddd-project with the actual path to your target project
ln -s /path/to/cursor-rules/generic-ddd-rule.yaml /path/to/your-ddd-project/.cursor-rules/generic-ddd-rule.yaml
```

Adjust the paths and filenames according to your specific structure and needs.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details (if one exists, otherwise state the license here directly).
