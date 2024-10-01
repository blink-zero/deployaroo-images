# Deployaroo VM Images Repository

![Deployaroo](https://img.shields.io/badge/Deployaroo-VM%20Images-blue)

Welcome to the Deployaroo VM Images repository. This repository contains various VM image playbooks that can be used with Deployaroo for deployment.

## Table of Contents

- [Introduction](#introduction)
- [VM Images](#vm-images)
  - [Non-Domain Images](#non-domain-images)
  - [Domain Images](#domain-images)
  - [Community Images](#community-images)
- [How to Use](#how-to-use)
  - [Uploading VM Images](#uploading-vm-images)
  - [Scanning for Images](#scanning-for-images)
  - [Viewing Image Details](#viewing-image-details)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction

Deployaroo simplifies the deployment of virtual machines by leveraging VMware Templates and Ansible. This repository contains default non-domain, domain, and community VM image playbooks that are pre-zipped and ready to use.

---

## VM Images

See [Documentation](https://deployaroo.io/download-images/)

---

## How to Use

### Uploading VM Images

1. **Navigate to VM Images Section**
   - Go to **Settings** in the Deployaroo application.
   - Select **Virtual Machine Images**.

2. **Upload Zip File**
   - Click the `Upload Zip` button at the top right of the screen.
   - Select the zip file containing your VM images and click `Open`.
   - The upload will begin immediately. Once complete, the new VM images will be added to the list.

### Scanning for Images

1. **Initiate Scan**
   - Click the `Scan Images` button at the top right of the **Virtual Machine Images** page.
   - The application will start scanning for new or updated VM images.

2. **Update List**
   - The scan process will automatically detect and add any new VM images to the list.
   - You will see a notification once the scan is complete, and the list will be refreshed with the latest images.

### Viewing Image Details

1. **Select Image**
   - On the **Virtual Machine Images** page, find the image you want to view.
   - Click the `Details` button next to the image for details.
   - Click on the `View Playbook` button to see the playbook.

---

## Contributing

We welcome contributions from the community! To submit your VM image:

1. **Prepare Your Image**
   - It is recommended to use a base of one of the current playbook main.yaml files and settings.json.
   - Create a zip file containing the modified main.yml and settings.json.
   - Ensure your folder name and ansible match name does not conflict with any of the [current ones](MATRIX.md) in the [MATRIX](MATRIX.md).
   - Test your image upload to Deployaroo.

2. **Submit Your Image**
   - Fork this repository to your GitHub account.
   - Add your zip file to the community image folder in your forked repository.
   - Commit the changes and create a pull request to the original repository.

3. **Provide Details**
   - In the pull request description, provide detailed information about your VM image, including:
     - Image type (non-domain, domain, etc.)
     - Use case
     - Any special configurations + installation

---

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
