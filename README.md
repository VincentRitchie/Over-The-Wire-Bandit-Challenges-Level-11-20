# Over-The-Wire-Bandit-Challenges-Level-11-20
This repository contains detailed walkthroughs and solutions for Levels 11 to 20 of the OverTheWire Bandit wargame. The Bandit challenge is designed to teach basic concepts of security and penetration testing through practical exercises. Each level of the challenge introduces new techniques and tools, gradually increasing in complexity.

#### Level 11 - 20

## Levels Contents

- [Level 11](#level-11)
- [Level 12](#level-12)
- [Level 13](#level-13)
- [Level 14](#level-14)
- [Level 15](#level-15)
- [Level 16](#level-16)
- [Level 17](#level-17)
- [Level 18](#level-18)
- [Level 19](#level-19)
- [Level 20](#level-20)

# Level 11

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20banditcover.png" height="350" width="500" />
</a>

## Level 11 Table of Contents
- [Description](#description)
- [Pseudocode](#pseudocode)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)

### Description
In Level 11 of the OverTheWire Bandit challenge, you need to use the `base64` command to decode a file.

### Pseudocode
```
1. Open the terminal.
2. Use SSH to connect to the Bandit server:
   ```
   ssh bandit11@bandit.labs.overthewire.org -p 2220
   ```
3. Enter the password: `<password_from_level_10>`.
4. Locate the file containing the encoded text.
5. Use the `base64 -d` command to decode the contents of the file:
   ```
   base64 -d <filename>
   ```
6. The output will display the password for the next level.
7. Record the password for use in the next level.
```

### Features
- **Base64 Encoding/Decoding:** Learn to encode and decode base64 encoded files.
- **File Handling:** Manage and read files in a Unix-like environment.

### Installation
To begin the challenge, ensure you have a terminal with SSH capabilities:
```sh
ssh bandit11@bandit.labs.overthewire.org -p 2220
```

### Usage
Follow the steps in the pseudocode to connect to the Bandit server and retrieve the password for the next level.

### Level 11 Screenshot
<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-11-20/blob/main/OTW%20-%20Bandit%20Level%2011.png" alt="Bandit Level 11 Screenshot" width="650" />
</a>

<br>
<br>
<br>

# Level 12

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20banditcover.png" height="350" width="500" />
</a>

## Level 12 Table of Contents
- [Description](#description)
- [Pseudocode](#pseudocode)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)

### Description
In Level 12, you will encounter a hexdump that needs to be reverted to its original form using `xxd`.

### Pseudocode
```
1. Open the terminal.
2. Use SSH to connect to the Bandit server:
   ```
   ssh bandit12@bandit.labs.overthewire.org -p 2220
   ```
3. Enter the password: `<password_from_level_11>`.
4. Locate the file containing the hexdump.
5. Use the `xxd -r` command to reverse the hexdump back to the original file:
   ```
   xxd -r <filename>
   ```
6. The output will display the password for the next level.
7. Record the password for use in the next level.
```

### Features
- **Hexdump Reversion:** Learn to reverse engineer a hexdump to its original form.
- **Command Line Techniques:** Practice using `xxd` for file manipulation.

### Installation
To begin the challenge, ensure you have a terminal with SSH capabilities:
```sh
ssh bandit12@bandit.labs.overthewire.org -p 2220
```

### Usage
Follow the steps in the pseudocode to connect to the Bandit server and retrieve the password for the next level.

### Level 12 Screenshot
<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-11-20/blob/main/OTW%20-%20Bandit%20Level%2012.png" alt="Bandit Level 12 Screenshot" width="650" />
</a>

<br>
<br>
<br>

# Level 13

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20banditcover.png" height="350" width="500" />
</a>
## Level 13 Table of Contents
- [Description](#description)
- [Pseudocode](#pseudocode)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)

### Description
In Level 13, you'll learn how to send a file to a remote server using `nc` (Netcat).

### Pseudocode
```
1. Open the terminal.
2. Use SSH to connect to the Bandit server:
   ```
   ssh bandit13@bandit.labs.overthewire.org -p 2220
   ```
3. Enter the password: `<password_from_level_12>`.
4. Locate the file that needs to be sent.
5. Use the `nc` command to send the file to the given remote server:
   ```
   cat <filename> | nc <hostname> <port>
   ```
6. The server will respond with the password for the next level.
7. Record the password for use in the next level.
```

### Features
- **Netcat Usage:** Learn to use `nc` for sending and receiving files over a network.
- **Command Line Networking:** Practice basic networking concepts using command line tools.

### Installation
To begin the challenge, ensure you have a terminal with SSH capabilities:
```sh
ssh bandit13@bandit.labs.overthewire.org -p 2220
```

### Usage
Follow the steps in the pseudocode to connect to the Bandit server and retrieve the password for the next level.

### Level 13 Screenshot
<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-11-20/blob/main/OTW%20-%20Bandit%20Level%2011.png" alt="Bandit Level 13 Screenshot" width="650" />
</a>

<br>
<br>
<br>

# Level 14

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20banditcover.png" height="350" width="500" />
</a>

## Level 14 Table of Contents
- [Description](#description)
- [Pseudocode](#pseudocode)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)

### Description
In Level 14, you will learn to retrieve the password for the next level by sending it through a specific port using `telnet`.

### Pseudocode
```
1. Open the terminal.
2. Use SSH to connect to the Bandit server:
   ```
   ssh bandit14@bandit.labs.overthewire.org -p 2220
   ```
3. Enter the password: `<password_from_level_13>`.
4. Use the `telnet` command to connect to the server:
   ```
   telnet <hostname> <port>
   ```
5. The server will prompt for the password.
6. Enter the password to retrieve the next level password.
7. Record the password for use in the next level.
```

### Features
- **Telnet Usage:** Learn to use `telnet` for communication over a network.
- **Networking Basics:** Practice using networking tools for server communication.

### Installation
To begin the challenge, ensure you have a terminal with SSH capabilities:
```sh
ssh bandit14@bandit.labs.overthewire.org -p 2220
```

### Usage
Follow the steps in the pseudocode to connect to the Bandit server and retrieve the password for the next level.

### Level 14 Screenshot
<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-11-20/blob/main/OTW%20-%20Bandit%20Level%2014.png" alt="Bandit Level 14 Screenshot" width="650" />
</a>

<br>
<br>
<br>


# Level 15

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20banditcover.png" height="350" width="500" />
</a>
## Level 15 Table of Contents
- [Description](#description)
- [Pseudocode](#pseudocode)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)

### Description
In Level 15, you'll need to solve a problem involving a service listening on a specific port.

### Pseudocode
```
1. Open the terminal.
2. Use SSH to connect to the Bandit server:
   ```
   ssh bandit15@bandit.labs.overthewire.org -p 2220
   ```
3. Enter the password: `<password_from_level_14>`.
4. Locate the service running on the specific port.
5. Use the appropriate command to connect and interact with the service:
   ```
   nc <hostname> <port>
   ```
6. The service will provide the password for the next level.
7. Record the password for use in the next level.
```

### Features
- **Service Interaction:** Learn to interact with services running on specific ports.
- **Networking Commands:** Practice using `nc` to communicate with services.

### Installation
To begin the challenge, ensure you have a terminal with SSH capabilities:
```sh
ssh bandit15@bandit.labs.overthewire.org -p 2220
```

### Usage
<i>Follow the steps in the pseudocode to connect to the Bandit server and retrieve the password for the next level.</i>

### Level 15 Screenshot
<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-11-20/blob/main/OTW%20-%20Bandit%20Level%2015.png" alt="Bandit Level 15 Screenshot" width="650" />
</a>

<br>
<br>
<br>

# Level 16

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20banditcover.png" height="350" width="500" />
</a>

## Level 16 Table of Contents
- [Description](#description)
- [Pseudocode](#pseudocode)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)

### Description
In Level 16, you will need to use `ssh` with a private key to connect to a service and retrieve the password.

### Pseudocode
```
1. Open the terminal.
2. Use SSH to connect to the Bandit server:
   ```
   ssh bandit16@bandit.labs.overthewire.org -p 2220
   ```
3. Enter the password: `<password_from_level_15>`.
4. Use the `ssh` command with the private key to connect to the target service:
   ```
   ssh -i <private_key> <user>@<hostname>
   ```
5. The service will provide the password for the next level.
6. Record the password for use in the next level.
```

### Features
- **SSH Key Authentication:** Learn to use SSH keys for authentication.
- **Secure Connections:** Practice secure connection methods using SSH.

### Installation
To begin the challenge, ensure you have a terminal with SSH capabilities:
```sh
ssh bandit16@bandit.labs.overthewire.org -p 2220
```

### Usage
Follow the steps in the pseudocode to connect to the Bandit server and retrieve the password for the next level.

### Level 16 Screenshot
<a>
  <img src="#" alt="Bandit Level 16 Screenshot" width="650" />
</a>

<br>
<br>
<br>

# Level 17

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20banditcover.png" height="350" width="500" />
</a>

## Level 17 Table of Contents
- [Description](#description)
- [Pseudocode](#pseudocode)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)

### Description
In Level 17, you'll need to deal with a specific port and send a file using `nc` (Netcat) after converting it to hexadecimal format.

### Pseudocode
```
1. Open the terminal.
2. Use SSH to connect to the Bandit server:
   ```
   ssh bandit17@bandit.labs.overthewire.org -p 2220
   ```
3. Enter the password: `<password_from_level_16>`.
4. Convert the file to hexadecimal format using `xxd`:
   ```
   xxd -p <filename> | nc <hostname> <port>
   ```
5. The server will provide the password for the next level.
6. Record the password for use in the next level.
```

### Features
- **Hexadecimal Conversion:** Learn to convert files to hexadecimal format.
- **Netcat for Data Transfer:** Use `nc` for sending data over a network.

### Installation
To begin the challenge, ensure you have a terminal with SSH capabilities:
```sh
ssh bandit17@bandit.labs.overthewire.org -p 2220
```

### Usage
Follow the steps in the pseudocode to connect to the Bandit server and retrieve the password for the next level.

### Level 17 Screenshot
<a>
  <img src="#" alt="Bandit Level 17 Screenshot" width="650" />
</a>

<br>
<br>
<br>

# Level 18

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20banditcover.png" height="350" width="500" />
</a>

## Level 18 Table of Contents
- [Description](#description)
- [Pseudocode](#pseudocode)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)

### Description
In Level 18, you will need to connect to a port and provide a specific response based on the service requirements.

### Pseudocode
```
1. Open the terminal.
2. Use SSH to connect to the Bandit server:
   ```
   ssh bandit18@bandit.labs.overthewire.org -p 2220
   ```
3. Enter the password: `<password_from_level_17>`.
4. Connect to the service using `nc`:
   ```
   nc <hostname> <port>
   ```
5. The service will prompt you for a specific response.
6. Provide the correct response to receive the password for the next level.
7. Record the password for use in the next level.
```

### Features
- **Service Interaction:** Learn to interact with network services and provide responses.
- **Command Line Networking:** Practice using `nc` for service communication.

### Installation
To begin the challenge, ensure you have a terminal with SSH capabilities:
```sh
ssh bandit18@bandit.labs.overthewire.org -p 2220
```

### Usage
Follow the steps in the pseudocode to connect to the Bandit server and retrieve the password for the next level.

### Level 18 Screenshot
<a>
  <img src="#" alt="Bandit Level 18 Screenshot" width="650" />
</a>

<br>
<br>
<br>

# Level 19

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20banditcover.png" height="350" width="500" />
</a>

## Level 19 Table of Contents
- [Description](#description)
- [Pseudocode](#pseudocode)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)

### Description
In Level 19, you will need to handle a file using `grep` to find specific information.

### Pseudocode
```
1. Open the terminal.
2. Use SSH to connect to the Bandit server:
   ```
   ssh bandit19@bandit.labs.overthewire.org -p 2220
   ```
3. Enter the password: `<password_from_level_18>`.
4. Locate the file that needs to be searched.
5. Use the `grep` command to search for the required information:
   ```
   grep <pattern> <filename>
   ```
6. The output will provide the password for the next level.
7. Record the password for use in the next level.
```

### Features
- **File Searching:** Learn to use `grep` for searching within files.
- **Text Processing:** Practice extracting information based on patterns.

### Installation
To begin the challenge, ensure you have a terminal with SSH capabilities:
```sh
ssh bandit19@bandit.labs.overthewire.org -p 2220
```

### Usage
Follow the steps in the pseudocode to connect to the Bandit server and retrieve the password for the next level.

### Level 19 Screenshot
<a>
  <img src="#" alt="Bandit Level 19 Screenshot" width="650" />
</a>

<br>
<br>
<br>

# Level 20

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20banditcover.png" height="350" width="500" />
</a>
## Level 20 Table of Contents
- [Description](#description)
- [Pseudocode](#pseudocode)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)

### Description
In Level 20, you need to deal with a service running on a specific port and extract a hidden password.

### Pseudocode
```
1. Open the terminal.
2. Use SSH to connect to the Bandit server:
   ```
   ssh bandit20@bandit.labs.overthewire.org -p 2220
   ```
3. Enter the password: `<password_from_level_19>`.
4. Connect to the service running on the specified port:
   ```
   nc <hostname> <port>
   ```
5. The service will provide a challenge or hidden content.
6. Interact with the service as required to reveal the password for the next level.
7. Record the password for use in the next level.
```

### Features
- **Service Interaction:** Learn to interact with network services to obtain hidden information.
- **Network Security Practice:** Practice using `nc` to communicate with services.

### Installation
To begin the challenge, ensure you have a terminal with SSH capabilities:
```sh
ssh bandit20@bandit.labs.overthewire.org -p 2220
```

### Usage
Follow the steps in the pseudocode to connect to the Bandit server and retrieve the password for the next level.

### Level 20 Screenshot
<a>
  <img src="#" alt="Bandit Level 20 Screenshot" width="650" />
</a>
