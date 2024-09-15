# Genetic Inheritance of Blood Type Simulation

## Description
This project simulates the genetic inheritance of blood types over multiple generations using a simple model. Each person has two parents and two alleles that determine their blood type. The program creates a family tree, prints the blood types of each family member, and frees the allocated memory.

## Features
- Simulate genetic inheritance of blood types over multiple generations
- Create a family tree with specified generations
- Print the blood types of each family member
- Free allocated memory

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/genetic-inheritance-simulator.git
   ```
2. Navigate to the project directory:
   ```bash
   cd inheritance
   ```
3. Compile the code:
   ```bash
   make inheritance
   ```

## Usage
1. Run the application:
   ```bash
   ./inheritance
   ```
2. The program will create a family tree with three generations, print the blood types of each family member, and free the allocated memory.

## Example
```bash
$ ./inheritance
Child (Generation 0): blood type AO
    Parent (Generation 1): blood type AA
        Grandparent (Generation 2): blood type AO
        Grandparent (Generation 2): blood type AA
    Parent (Generation 1): blood type BO
        Grandparent (Generation 2): blood type BO
        Grandparent (Generation 2): blood type OO
```

![image](https://github.com/user-attachments/assets/f04cd3ff-72f6-42e0-9755-fb00bedcdcd9)
*Shows simulation of genetic inheritance according to a model of a 'family tree' with predetermined input!*  

## Contributing
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License
This project is not licensed under any License currently. 
