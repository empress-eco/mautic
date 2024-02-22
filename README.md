

<div align="center">

<img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Logo" width="80" height="80">

# Empress Mautic Integration


Welcome to Empress Mautic Integration, a powerful solution that seamlessly integrates your Empress system with Mautic, enhancing your marketing automation capabilities.

[Explore the Docs](https://grow.empress.eco/) |  [Report Bug](https://github.com/empress-eco/mautic/issues) | [Request Feature](https://github.com/empress-eco/mautic/issues/new)

</div>



## About The Project

Empress Mautic Integration is designed for Empress users looking to leverage the power of Mautic's marketing automation. It eliminates the tedious task of manual data transfer between your ERP and Mautic by automating the process. This not only saves time and reduces errors but also heightens your marketing efforts.

### Key Features

- Sync Mautic Segment with Empress "Mautic Segment"
- Link Mautic Company with Empress Customer
- Connect Mautic Contact with Empress Contact
- Map Empress Customer to Mautic Companies
- Align Empress Contact to Mautic Contact

## Technical Stack and Setup Instructions

This application requires Empress and Empress v10.0, v11.0 (not tested on higher versions).

### Installation

Clone the Empress Mautic Integration repository:

```sh
bench get-app mautic https://github.com/empress-eco/mautic.git
```

Install the application:

```sh
bench install-app mautic
```

Restart and migrate the bench:

```sh
bench restart && bench migrate
```

Refer to the Mautic and Empress Mautic configuration sections in the [documentation](https://grow.empress.eco/) for detailed setup instructions.

## Usage

After installation and configuration, the application is scheduled to run hourly by default. Ensure that your scheduler is enabled using the command: `bench enable-scheduler`.

## Contribution Guidelines

We greatly appreciate and value your contributions! Here's how you can contribute:

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

## License and Acknowledgements

### License

This project is under the MIT License. Your contributions are also licensed under the MIT License.

### Acknowledgements

We express our profound gratitude to the Empress Community, the architects behind the essential tools that power this project. Their innovation and dedication have been invaluable in building the foundations and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.