Malware Analysis Automation Project
Project Overview

This project automates the analysis of malware samples using Any.Run, Hybrid Analysis, and VirusTotal. The provided scripts facilitate tasks such as file submission, report retrieval, and feature extraction for API calls, network connections, registry modifications, and file system changes.
Table of Contents

    Getting Started
    System Requirements
    Setup Instructions
    Usage Instructions
    Terms of Use
    Privacy Policy
    Disclaimer

Getting Started

This project contains Python scripts and configuration files designed to automate malware analysis workflows. These scripts interact with sandboxing tools (Any.Run, Hybrid Analysis, VirusTotal) to streamline the retrieval of malware behavioral data.
System Requirements

    Python 3.8 or above
    Internet connection for API interactions
    API keys for Any.Run, Hybrid Analysis, and VirusTotal
    Supported operating systems: Linux, macOS, Windows

Setup Instructions

    Organize the project files:
        Place the provided scripts in a dedicated folder (e.g., malware_analysis_project).
        Ensure the following subdirectories are created:

    malware_analysis_project/
    ├── config/                  # For API configuration files
    ├── scripts/                 # For analysis scripts
    └── data/samples/            # For malware samples

Install required Python packages:

    Use the following command to install dependencies:

        pip install requests

    Configure API keys:
        Open the config/ directory and update the following files with your API keys:
            config_anyrun.py
            config_hybrid.py
            config_virustotal.py

Usage Instructions

    Place your malware samples in the data/samples/ directory.

    Run individual scripts for each sandboxing tool:
        For Any.Run:

python scripts/anyrun_analysis.py

For Hybrid Analysis:

python scripts/hybrid_analysis.py

For VirusTotal:

        python scripts/virustotal_analysis.py

    Extract key features from the JSON reports using the report_parser.py script.

Terms of Use

    This project and its contents are provided solely for educational and research purposes.
    Users must comply with all applicable laws and regulations when using this project.
    The provided scripts, data, and configurations must not be used in real-world production systems, malicious activities, or unauthorized cybersecurity operations.
    By using this repository, you agree to take full responsibility for your actions and acknowledge that the authors are not liable for any misuse.

Privacy Policy

    This project does not collect or process any user data beyond what is necessary to run the provided scripts.
    Any API keys or configurations provided by the user remain local and are not transmitted or stored elsewhere by this project.
    Users are responsible for securing their API keys and ensuring compliance with the privacy policies of Any.Run, Hybrid Analysis, and VirusTotal.

Disclaimer

    The provided code and data are not intended for real production environments. They are designed exclusively for research and educational purposes.
    The authors do not guarantee the accuracy, reliability, or security of the scripts. Use them at your own risk.
    The authors are not responsible for any consequences resulting from the use of this project, including but not limited to:
        Damage to systems or devices
        Legal repercussions
        Violations of third-party terms or policies
    It is the user's responsibility to ensure compliance with the terms of use for Any.Run, Hybrid Analysis, and VirusTotal.

Acknowledgments

This project was developed to demonstrate automation workflows in malware analysis. Special thanks to Any.Run, Hybrid Analysis, and VirusTotal for providing APIs and platforms that support research in cybersecurity.
Contact Information

For questions or issues, please contact:
Tyller Ferderer
tef5155@psu.edu
