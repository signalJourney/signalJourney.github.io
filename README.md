# signalJourney.github.io

This repository hosts the official documentation website for the [Signal Journey](https://github.com/signalJourney/signalJourney) project.

## 🌐 Live Site

The documentation is automatically deployed to: **https://signaljourney.github.io/**

## 🔄 Automatic Deployment

This repository's content is automatically generated and deployed by the CI/CD pipeline from the main [signalJourney/signalJourney](https://github.com/signalJourney/signalJourney) repository.

**Please do not manually edit files in this repository** - all changes should be made to the documentation source files in the main repository under the `docs/` directory.

## 📚 Documentation Source

- **Main Repository**: [signalJourney/signalJourney](https://github.com/signalJourney/signalJourney)
- **Documentation Source**: [`docs/` directory](https://github.com/signalJourney/signalJourney/tree/main/docs)
- **Build Configuration**: [`mkdocs.yml`](https://github.com/signalJourney/signalJourney/blob/main/mkdocs.yml)

## 🛠️ How It Works

1. Changes are made to documentation files in the main repository
2. When changes are pushed to the `main` branch, the CI workflow automatically:
   - Builds the documentation using MkDocs
   - Deploys the generated static site to this repository
   - Updates the live website at https://signaljourney.github.io/

## 📝 Contributing to Documentation

To contribute to the documentation:

1. Fork the main [signalJourney/signalJourney](https://github.com/signalJourney/signalJourney) repository
2. Make changes to files in the `docs/` directory
3. Submit a pull request to the main repository
4. Once merged, the documentation will be automatically updated here

For detailed contribution guidelines, see the main repository's [CONTRIBUTING.md](https://github.com/signalJourney/signalJourney/blob/main/CONTRIBUTING.md).

## 📄 License

This documentation is licensed under the same [BSD 3-Clause License](https://github.com/signalJourney/signalJourney/blob/main/LICENSE) as the main Signal Journey project.
