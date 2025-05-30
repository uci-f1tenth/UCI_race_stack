<!-- Project Title and Subtitle -->

<div align="center">

# F1Tenth @ UCI_race_stack

**A Race Car Simulation**

*powered by DreamerV3*
</div>

<!-- Project Shields -->

<div align="center">

[![License][license-shield]][license-url]
[![Contributors][contributors-shield]][issues-url]
[![Forks][forks-shield]][forks-url]
[![Stars][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

<a href="https://github.com/uci-f1tenth/UCI_race_stack/blob/main/CONTRIBUTING.md">Get Started</a>
&middot;
<a href="https://github.com/uci-f1tenth/UCI_race_stack/blob/main/docs/Development_Guide.pdf">Documentation</a>
&middot;
<a href="https://github.com/uci-f1tenth/UCI_race_stack/issues/new?template=issue.md">Report Bug</a>

</div>

<!-- Table of Contents -->

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#introduction">Introduction</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#features">Features</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#testiing">Testing</a></li>
    <li><a href="#checklist">Checklist</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

<!-- Contents -->

## Introduction

We add [DreamerV3](https://arxiv.org/abs/2301.04104) implementations of World Models into the F1tenth ROS2 environment in PyTorch.

### Built With

We referenced the following repositories for the base code:

- [dreamerv3-torch](https://github.com/NM512/dreamerv3-torch)

- [racing_dreamer](https://github.com/CPS-TUWien/racing_dreamer)

- [dreamerv3](https://github.com/danijar/dreamerv3)

## Features

This project:

- **Bridges** the gap between 1D LiDAR data and DreamerV3's input requirements.

- **Includes** a custom development environment (Gymnasium).

- **Leverages** multi-core training environment to maximize computational efficiency.

- **Provides** seamless integration with the ROS2 framework.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please reference [CONTRIBUTING.md](CONTRIBUTING.md) for detailed contribution guide.

## Testing

- [x] implemented f1tenth gym for testing environment.
- [ ] waiting on issac sim implementation for better simulation environment.

## Checklist

- [x] basic structure implementation(bare bones)
- [ ] LiDAR feed for encoded latent state
- [ ] World Model implementation
- [ ] Actor-Critic implementation
- [ ] Scaling reward system

## License

This project is licensed under the [MIT](LICENSE) license. 

<!-- Link Definitions -->

[license-shield]: https://img.shields.io/github/license/uci-f1tenth/UCI_race_stack?style=plastic
[license-url]: https://github.com/uci-f1tenth/UCI_race_stack?tab=MIT-1-ov-file
[contributors-shield]: https://img.shields.io/github/contributors/uci-f1tenth/uci_f1tenth_workshop?style=plastic
[contributors-url]: https://github.com/uci-f1tenth/uci_f1tenth_workshop/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/uci-f1tenth/uci_f1tenth_workshop?style=plastic
[forks-url]: https://github.com/uci-f1tenth/uci_f1tenth_workshop/forks
[stars-shield]: https://img.shields.io/github/stars/uci-f1tenth/uci_f1tenth_workshop?style=plastic
[stars-url]: https://github.com/uci-f1tenth/uci_f1tenth_workshop/stars
[issues-shield]: https://img.shields.io/github/issues/uci-f1tenth/uci_f1tenth_workshop?style=plastic
[issues-url]: https://github.com/uci-f1tenth/uci_f1tenth_workshop/issues
