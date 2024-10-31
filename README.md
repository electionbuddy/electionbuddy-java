# ElectionBuddy Java SDK

The official Java SDK for [ElectionBuddy](https://electionbuddy.com)'s API. This library provides a convenient way to interact with ElectionBuddy's API services from your Java applications.

## Requirements

- Java 21 or higher
- Gradle 8.10 or higher

## Development

### Building the Project

```bash
./gradlew build
```

### Running Tests

```bash
./gradlew test
```

### Publishing

This project uses GitHub Actions for automated publishing. To publish a new version:

1. Update the version in `build.gradle.kts`
2. Create and push a new tag:
```bash
git tag v0.1.0
git push origin v0.1.0
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

If you encounter any problems or have questions:
- Open an issue in the GitHub repository
- Contact ElectionBuddy support
- Check the [API documentation](https://electionbuddy.com/api-docs)
