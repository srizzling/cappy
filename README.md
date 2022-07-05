<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/srizzling/cappy">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">cappy</h3>

  <p align="center">
    A cli to simplify switching and logging into multiple AWS accounts and roles with ease
  </p>
</p>

<!-- ABOUT THE PROJECT -->

## About The Project

This CLI simplifies the use of saml2aws by allowing you quickly (and safely) switch between multiple roles and accounts using auto-complete and safe profile switching

### Built With

- [srizzling/cookiecutter-golang-cli](https://github.com/srizzling/cookiecutter-golang-cli)
- [mitchelh/cli](https://github.com/mitchellh/cli)

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

- go1.14

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com//srizzling/cappy.git
   ```
2. Install and tidy up go modules
   ```sh
   make vendor
   ```
3. Build a binary
   ```sh
   make build
   ```

## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

## Roadmap

See the [open issues](https://github.com/srizzling/cappy/issues) for a list of proposed features (and known issues).

## Releases

Releases are automatically created upon commits landing in main. These will autotrigger new version and release in Github.

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the unlicense License. See `LICENSE` for more information.
