# alexm-dev/scoop-bucket

**Personal Scoop Bucket** for [Scoop](https://scoop.sh/) Windows package manager.

## About

This is [alexm-dev](https://github.com/alexm-dev)'s custom [Scoop](https://scoop.sh/) bucket, providing manifests for easy installation of software that isn't found in the main Scoop repositories.

Current bucket contents:

- `runa` ([repo](https://github.com/alexm-dev/runa)) &mdash; A lightweight terminal file browser written in Rust

## Usage

First, [install Scoop](https://scoop.sh/).

Then add this bucket:

```powershell
scoop bucket add alexm-dev https://github.com/alexm-dev/scoop-bucket
```

Install an app from your bucket:

```powershell
scoop install runa
```

## Contributing

Contributions are welcome! To add or update a manifest, fork this repo and open a pull request.

## License

The manifest files and scripts in this bucket are licensed under the MIT license:

- [License](LICENSE)


_This license applies only to the manifests/scripts in this repo. For the actual software installed via manifests, see each project’s own license._

