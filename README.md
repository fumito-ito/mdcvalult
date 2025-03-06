# MDC Valult

Welcome to **MDC Valult**—a curated repository of context-specific `.mdc` files designed to streamline your workflows and boost productivity!

## How to use

You can use these `.mdc` files from [`projectrules` CLI](https://github.com/fumito-ito/ProjectRules).

```bash
$ brew tap fumito-ito/projectrules
$ brew install projectrules

# Generate multiple .mdc files in specified directory
$ projectrules best-practices-for-writitng-nextjs,guidelines-for-writing-postgres-sql-by-supabase -t .cursor/rules
```

## File Naming Conventions

- **Lowercase & Simple:**  
  All MDC file names **must use lowercase alphanumeric characters** and may include hyphens (e.g., `unit-test-guidelines.mdc`).

- **File Extension:**  
  Every file in this repository must have the `.mdc` extension.

- **Descriptive Names:**  
  Choose file names that **concisely and clearly describe the rule’s content**. This helps ensure that each file communicates its purpose at a glance.

## Content Guidelines

- **Context-Specific:**  
  Each `.mdc` file should address a **specific context or scenario**. Avoid bundling rules that cover an overly broad scope into a single file.

- **Quality Over Quantity:**  
  Focus on creating precise, actionable rules that improve your project’s workflow rather than trying to cover everything in one file.

## Contributing

We love contributions! If you've created an excellent MDC file that follows these guidelines, please consider opening a pull request. Your contributions will help us grow a community-driven resource for high-quality project rules.

## License

This repository is licensed under the **MIT License**. All `.mdc` files contained within this repository are also covered by the same license.

---

Happy coding and rule-making!
