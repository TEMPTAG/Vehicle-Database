## <a name="top"></a>

# Vehicle Database CLI Application

![GitHub License](https://img.shields.io/github/license/TEMPTAG/readme-gen?label=License)

---

## Description

This Vehicle Datatbase Command-Line Application lets users creat, manage, and perform various actions on different types of vehicles, specifically; Cars, Trucks, and Motorbikes. Using TypeScript ensures type safety, and the Inquirer.js Package provides the backbone of this interactive CLA.

<!-- Screenshot and link to walkthrough video -->

![Screenshot of Application Sample]()
[You can see a video of the application in action HERE]()

Hi, I am Ian Ferguson, and this fun CLI application allows you to play with the provided vehicles or create your own. Each vehicle has its own inputs, abilities, and feedback to your inputs. Play around with it and let me know what you think. Future work will include more specific inputs, more requirements, and more defaults if inputs are left blank.

---

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)
- [License](#license)

---

## Installation

Before you get started, you will need to have installed:

- [Node.js](https://nodejs.org/)
- [TypeScript](https://www.typescriptlang.org/)

**To install this project locally, jump into your terminal application and please follow these steps**:

1. Clone the `Vehicle-Database` Repository to your local machine - first navigate to the directory you would like to clone it into, then:

```bash
Using HTTPS:
git clone https://github.com/TEMPTAG/Vehicle-Database.git

Using SSH:
git clone git@github.com:TEMPTAG/Vehicle-Database.git

Using GitHub CLI:
gh repo clone TEMPTAG/Vehicle-Database
```

2. Navigate into the `Vehicle-Database` directory you just cloned down:

```bash
cd Vehicle-Database
```

3. Install the Dependencies:

```bash
npm install
```

---

## Usage

**Once you have cloned the project and installed the dependencies, you can run the command-line application in your terminal and manage your Vehicle Database!**

1.  Navigate into to the `Vehicle-Database` project directory:

    ```bash
    cd Vehicle-Database
    ```

2.  Run the `Vehicle-Database` application:

    ```bash
    npm start
    ```

3.  Start by selecting between creating a new vehicle, or selecting an existing vehicle. Navigate between the options with the up/down arrows and selecting by hitting enter:

    ```bash
    ? Would you like to create a new vehicle or perform an action on an existing vehicle? (Use arrow keys)
    ❯ Create a new vehicle
    Select an existing vehicle
    ```

4.  Selecting `Create a new vehicle`:

    - You will have the option to select between creating a new `Car`, `Truck`, or `Motorbike`:

      ```bash
      ? Select a vehicle type (Use arrow keys)
      ❯ Car
      Truck
      Motorbike
      ```

    - Once you select the vehicle type, you are prompted to input values specific to creating each vehicle type:

      - `Car`:

        ```bash
        ? Select a vehicle type Car
        ? Enter Color
        ? Enter Make
        ? Enter Model
        ? Enter Year
        ? Enter Weight
        ? Enter Top Speed
        ```

        > **NOTE**:
        > _VIN information is auto-generated, and 4 default wheel obejects will be added to the_ `Car`

      - `Truck`:

        ```bash
        ? Select a vehicle type Truck
        ? Enter Color
        ? Enter Make
        ? Enter Model
        ? Enter Year
        ? Enter Weight
        ? Enter Top Speed
        ? Enter Towing Capacity  #Only on vehicle type Truck
        ```

        > **NOTE**:
        > _VIN information is auto-generated, and 4 default wheel obejects will be added to the_ `Truck`

      - `Motorbike`:

        ```bash
        ? Select a vehicle type Motorbike
        ? Enter Color
        ? Enter Make
        ? Enter Model
        ? Enter Year
        ? Enter Weight
        ? Enter Top Speed
        ? Enter Wheel Diameter in Inches  #Only on vehicle type Motorbike
        ? Enter Tire Brand  #Only on vehicle type Motorbike
        ```

        > **NOTE**:
        > _VIN information is auto-generated, and default vaules will be added to the 2_ `Motorbike` _wheel objects if no values are entered for 'Wheel Diameter' and/or 'Tire Brand'_

5.  After entering the values above you are able to then perform `actions` on that vehicle, select or create another vehicle, or exit the application:

    ```bash
    ? Select an action (Use arrow keys)
    ❯ Print details
    Start vehicle
    Accelerate 5 MPH
    Decelerate 5 MPH
    Stop vehicle
    Turn right
    Turn left
    Reverse
    Tow   #Only applies to vehicle type Trucks
    Wheelie  #Only applies to vehicle type Motorbikes
    Select or create another vehicle
    Exit
    ```

Have fun and enjoy this simple Vehicle Database through using existing vehicles in the database, adding your own vehicles, and performing basic actions on all of the vehiles!

---

## Contributing

![GitHub contributors](https://img.shields.io/github/contributors/TEMPTAG/Vehicle-Database?color=green) ![GitHub commit activity](https://img.shields.io/github/commit-activity/t/TEMPTAG/Vehicle-Database) ![GitHub top language](https://img.shields.io/github/languages/top/TEMPTAG/Vehicle-Database)

OH. MY. GOODNESS. Collaborations are amazing. Share ideas, code, etc. with others is the best way to share knowledge, mutual enthusiasms, and a lot of times we make cool friends along the way. I welcome contributions in many ways, shapes, and forms:

- [Email Me](mailto:iansterlingferguson@gmail.com) and just plain tell me what you like, do not like, would like to see changed... just give me a compliment before laying it on me
- FORK IT ALL - create a fork, clone it down, mess it up, do the neato commits and comments, push it back, test it at least a million times, then submit a pull request for me to review and merge into the project if I think you are cool (and the code is cool too) - but again, the nice thing to do would be emailing me first and telling me your intentions... and don't forget the compliment part

Something, something... Have your people call my people. And by call, I mean email - who answers the phone these days?

---

## Tests

As the above states, please test your changes thoroughly before submitting a pull request or sending it straight to me. As far as tests I have done? None. Zero. Ziltch. I have not learned how to do that yet, so I am relying on you to do your part until I learn how to do mine.

---

## Questions

Have questions about this project? Want to collaborate? Eager to discuss conspiracy theories or debate why your favorite car is not as cool as you think? [Email Me](mailto:iansterlingferguson@gmail.com) — just do not call, because I probably will not answer.

Did this project make your life better in any way, shape, or form? Check out my other exceptionally rare moments of lucidity on my [GitHub Profile](https://github.com/TEMPTAG)

---

## License

This project is covered under the MIT License. The details of the MIT License can be found on their site [HERE](https://opensource.org/licenses/MIT). You can also see the full details of the [LICENSE](./LICENSE) for this specific project in the linked file.

---

<div align="center">
<em>Copyright © 2024 Ian Ferguson - powered by caffine, love, and a little bit of fun</em>

[Back to top](#top)

</div>
