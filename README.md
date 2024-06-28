# ethavax
# DrivingLicense Smart Contract
This contract helps manage driving licenses. Users can set their age and whether they own a vehicle. The contract can then check if they are eligible for a driving license.

## Requirements
Solidity version ^0.8.0
A development environment like Remix, Truffle, or Hardhat
## License
This project is not open-source. It uses the UNLICENSED license.

## Contract Details
### Variables
age: Keeps track of each user's age.
ownsVehicle: Keeps track of whether each user owns a vehicle.
### Functions
setAge(uint _age): Sets the user's age. The age must be between 1 and 149.
setVehicleOwnership(bool _ownsVehicle): Sets whether the user owns a vehicle.
checkEligibility(): Checks if the user can get a driving license. The user must be at least 18 years old and own a vehicle.
