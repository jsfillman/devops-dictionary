# Custom LocalDictionary for macOS Transcription

This repository contains a custom `LocalDictionary` file for macOS transcription, optimized for DevOps, Bash, and Python scripting terms and acronyms. This custom dictionary improves the accuracy of transcriptions involving technical jargon that is not typically included in standard dictionaries.

## Contents

- **LocalDictionary.txt**: The custom dictionary file containing technical terms and acronyms.

## Installation

To integrate this custom dictionary into your macOS system, follow these steps:

1. **Clone the Repository.**
   Open Terminal and clone this repository to your local machine:
   
   ```sh
   git clone https://github.com/yourusername/custom-localdictionary.git
   cd custom-localdictionary
   ```
2. **Copy the Custom Dictionary File.**
  Copy the contents of the LocalDictionary.txt file to your macOS LocalDictionary file:

   ```sh
   cat LocalDictionary.txt >> ~/Library/Spelling/LocalDictionary
   ```

3. **Restart Applications.** Restart any applications where you want the custom dictionary to take effect to ensure they recognize the new terms. (Or just log out and back in!)
