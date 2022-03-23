<p align="center">
  <img width=256px src="./docs/promotional/logo.png" />
  <h1 align="center">Intero</h1>
  <p align="center">
    Intero is an AI powered design tool, which can use user-inputted text to generate floor plan schematics, plot them on paper, print them and store them digitally.
  </p>
</p>

<p align="center">
    <a href="https://github.com/braind3d/intero/fork">
        <img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat-square" alt="Contributions welcome badge" />
    </a>
    <a href="LICENSE">
        <img src="https://img.shields.io/github/license/braind3d/intero?style=flat-square" alt="License badge" />
    </a>
</p>


## Get started

The project consists of 4 main components:
- **Machine learning algorithm**, for generating floor plans based on text room description input (located in "[intero-ai](https://github.com/braind3d/intero-ai)")
- **Backend API & Web client**, which provide an interface for drawing and generating floor plans, printing and plotting them, etc. (located in "[intero-server](https://github.com/braind3d/intero-server)")
- **XY-Plotter**, which can draw the created floor plan onto paper (located in"[intero-plotter](https://github.com/braind3d/intero-plotter)")
- **Deployment infrastructure**, which define the project infrastructure and  in the cloud (located in"[intero-infrastructure](https://github.com/braind3d/intero-infrastructure)")

For each of the components' repositories there is a corresponding `README.md` with instructions on how to get started.


## Development setup
1. Clone the project repository and its submodules.
```
git clone https://github.com/braind3d/intero --recursive
cd intero
```

2. Checkout all submodules to the main branch.
```
git submodule foreach --recursive git checkout main
```

3. Follow the instruction in each individual submodule.


## Authors
<table width="100%">
  <tr>
    <td>
        <img width="500px" src="https://github.com/angel-penchev.png" alt="Angel Penchev's profile picture" />
        <p align="center">
            <b>Angel Penchev</b>
            <a href="https://github.com/angel-penchev/">
                <img src="https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white" />
            </a>
        </p>
    </td>
    <td>
        <img width="500px" src="https://github.com/Maddie02.png" alt="Madlen Sarkisian's profile picture" />
        <p align="center">
            <b>Madlen Sarkisian</b>
            <a href="https://github.com/Maddie02/">
                <img src="https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white" />
            </a>
        </p>
    </td>
    <td>
        <img width="500px" src="https://github.com/bobig6.png" alt="Boyan Ivanov's profile picture" />
        <p align="center">
            <b>Boyan Ivanov</b>
            <a href="https://github.com/bobig6/">
                <img src="https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white" />
            </a>
        </p>
    </td>
    <td>
        <img width="500px" src="https://github.com/IlianaGenova.png" alt="Iliana Genova's profile picture" />
        <p align="center">
            <b>Iliana Genova</b>
            <a href="https://github.com/IlianaGenova/">
                <img src="https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white" />
            </a>
        </p>
    </td>
    <td>
        <img width="500px" src="https://github.com/simo1209.png" alt="Simeon Georgiev's profile picture" />
        <p align="center">
            <b>Simeon Georgiev</b>
            <a href="https://github.com/simo1209/">
                <img src="https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white" />
            </a>
        </p>
    </td>
  </tr>
</table>


## Contributions
1. Fork it (<https://github.com/braind3d/intero/fork>)
2. Create your feature branch (`git checkout -b feat-###`)
3. Commit your changes (`git commit -a`)
4. Push to the branch (`git push origin feat-###`)
5. Create a new Pull Request
6. Upon review it will be merged.


## License
Distributed under the BSD-3 Cause license. See [LICENSE](LICENSE) for more information.
