# DigiTrust ICP Integration

This project integrates DigiTrust with Internet Computer Protocol (ICP) canisters. It consists of two main components:

1. UI Application (`app` folder)
2. Canister Service (`canister_service` folder)

## Project Structure

- `app/`: Contains the frontend UI application
- `canister_service/`: Contains the backend canister code

## UI Application (app)

The `app` folder contains the frontend application built with React. It includes:

- Components
- Hooks
- Theme configuration
- Utility functions
- Localization support

## Canister Service (canister_service)

The `canister_service` folder contains the backend code for building and deploying ICP canisters. It includes:

- `dfx` configuration
- Canister source code
- Test files

## Setup and Running

To start the canister service:

```
cd canister_service
dfx start --clean --background
```