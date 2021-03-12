  <h1 align="center">Scotland Yard</h1>
  <p align="center">
    Implementation of the Scotland Yard Board       Game for COMS10009 Object-Oriented Programming 
    <br />
    <a href="https://github.com/AbdizamedAli/repo_name/issues">Report Bug</a>
    ·
    <a href="https://github.com/AbdizamedAli/repo_name/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
This is an implementation of the board game scotland yard for the COMS10009 unit. We have also added an AI for MrX that uses Djikstras algorithm to find the shortest path  and looks ahead by one move move iteration to return a move.


### Built With

* [Willam Naffack](https://github.com/willianck)



## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* maven
  ```sh
  sudo apt install maven
  ```
* java 11
  ```sh
    sudo apt update
    sudo apt intall openjdk-11-jdk
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/github_username/ScotlandYard.git
   ```

<!-- USAGE EXAMPLES -->
## Usage
1. Compile project
   ```sh
   Linux:   ./mvnw clean compile
   Windows:  mvnw clen compile
   ```
2. Run tests  
    ```sh 
    Linux:   ./mvnw clean test
    Windows:  mvnw clean test
    ```
3. Start up GUI
    ```sh 
    Linux: ./mvnw clean compile exec:java
    Windows: mvnw clean compile exec:java
    ```