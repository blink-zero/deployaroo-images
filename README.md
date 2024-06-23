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

### Non-Domain Images
**Currently: 16**

| Image Name                                          | Author        | Image Type  | OS                                   | Description                                                                                             | Download Link                                               |
|-----------------------------------------------------|---------------|-------------|--------------------------------------|---------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| CentOS 7 - GUI                                      | blink-zero    | Non-Domain  | CentOS 7                             | Automates deployment of CentOS 7 VM with GUI, including network config and final reboot.                | [Download](images/non-domain/vmware_create_linux_centos7_gui.zip) |
| CentOS 7 - Minimal                                  | blink-zero    | Non-Domain  | CentOS 7                             | Minimal installation of CentOS 7 VM.                                                                    | [Download](images/non-domain/vmware_create_linux_centos7_minimal.zip)                   |
| Kali 2024.1                                         | blink-zero    | Non-Domain  | Kali 2024.1                          | Kali Linux 2024.1 VM image for non-domain environments.                                                 | [Download](images/non-domain/vmware_create_linux_kali2024.1.zip)                         |
| Ubuntu 18.04 - GUI                                  | blink-zero    | Non-Domain  | Ubuntu 18.04                         | Ubuntu 18.04 VM with GUI for non-domain use.                                                            | [Download](images/non-domain/vmware_create_linux_ubuntu18.04_gui.zip)                    |
| Ubuntu 18.04 - Minimal                              | blink-zero    | Non-Domain  | Ubuntu 18.04                         | Minimal installation of Ubuntu 18.04 VM.                                                                | [Download](images/non-domain/vmware_create_linux_ubuntu18.04_minimal.zip)                |
| Ubuntu 20.04 - GUI                                  | blink-zero    | Non-Domain  | Ubuntu 20.04                         | Ubuntu 20.04 VM with GUI for non-domain use.                                                            | [Download](images/non-domain/vmware_create_linux_ubuntu20.04_gui.zip)                    |
| Ubuntu 20.04 - Minimal                              | blink-zero    | Non-Domain  | Ubuntu 20.04                         | Minimal installation of Ubuntu 20.04 VM.                                                                | [Download](images/non-domain/vmware_create_linux_ubuntu20.04_minimal.zip)                |
| Ubuntu 22.04 - GUI                                  | blink-zero    | Non-Domain  | Ubuntu 22.04                         | Ubuntu 22.04 VM with GUI for non-domain use.                                                            | [Download](images/non-domain/vmware_create_linux_ubuntu22.04_gui.zip)                    |
| Ubuntu 22.04 - Minimal                              | blink-zero    | Non-Domain  | Ubuntu 22.04                         | Minimal installation of Ubuntu 22.04 VM.                                                                | [Download](images/non-domain/vmware_create_linux_ubuntu22.04_minimal.zip)                |
| Ubuntu 22.04 - Developer                            | blink-zero    | Non-Domain  | Ubuntu 22.04                         | Developer edition of Ubuntu 22.04 VM for non-domain use.                                                | [Download](images/non-domain/vmware_create_linux_ubuntu22.04_developer.zip)              |
| Windows 10 Pro                                      | blink-zero    | Non-Domain  | Windows 10 Professional              | Windows 10 Pro VM for non-domain environments.                                                          | [Download](images/non-domain/vmware_create_windows_10pro.zip)                      |
| Windows Server 2019 Datacenter - Core               | blink-zero    | Non-Domain  | Windows Server 2019 Datacenter       | Windows Server 2019 Datacenter Core VM for non-domain environments.                                     | [Download](images/non-domain/vmware_create_windows_server2019dc_core.zip)            |
| Windows Server 2019 Datacenter - Desktop Experience | blink-zero    | Non-Domain  | Windows Server 2019 Datacenter       | Windows Server 2019 Datacenter Desktop Experience VM for non-domain environments.                       | [Download](images/non-domain/vmware_create_windows_server2019dc_de.zip)         |
| Windows Server 2022 Datacenter - Core               | blink-zero    | Non-Domain  | Windows Server 2022 Datacenter       | Windows Server 2022 Datacenter Core VM for non-domain environments.                                     | [Download](images/non-domain/vmware_create_windows_server2022dc_core.zip)            |
| Windows Server 2022 Datacenter - Desktop Experience | blink-zero    | Non-Domain  | Windows Server 2022 Datacenter       | Windows Server 2022 Datacenter Desktop Experience VM for non-domain environments.                       | [Download](images/non-domain/vmware_create_windows_server2022dc_de.zip)         |
| Windows Server 2022 Datacenter - Active Directory   | blink-zero    | Non-Domain  | Windows Server 2022 Datacenter       | Windows Server 2022 Datacenter Desktop Experience VM with Active Directory for non-domain environments. | [Download](images/non-domain/vmware_create_windows_server2022dc_de_ad.zip)      |


### Domain Images
**Currently: 9**

| Image Name                                          | Author        | Image Type  | OS                                   | Description                                                                                             | Download Link                                       |
|-----------------------------------------------------|---------------|-------------|--------------------------------------|---------------------------------------------------------------------------------------------------------|-----------------------------------------------------|
| CentOS 7 - Minimal                                  | blink-zero    | Domain      | CentOS 7                             | Minimal installation of CentOS 7 VM for domain environments.                                            | [Download](images/domain/vmware_create_domain_linux_centos7_minimal.zip)       |
| Ubuntu 18.04 - Minimal                              | blink-zero    | Domain      | Ubuntu 18.04                         | Minimal installation of Ubuntu 18.04 VM for domain environments.                                        | [Download](images/domain/vmware_create_domain_linux_ubuntu18.04_minimal.zip) |
| Ubuntu 20.04 - Minimal                              | blink-zero    | Domain      | Ubuntu 20.04                         | Minimal installation of Ubuntu 20.04 VM for domain environments.                                        | [Download](images/domain/vmware_create_domain_linux_ubuntu20.04_minimal.zip) |
| Ubuntu 22.04 - Minimal                              | blink-zero    | Domain      | Ubuntu 22.04                         | Minimal installation of Ubuntu 22.04 VM for domain environments.                                        | [Download](images/domain/vmware_create_domain_linux_ubuntu22.04_minimal.zip) |
| Windows 10 Pro                                      | blink-zero    | Domain      | Windows 10 Professional              | Windows 10 Pro VM for domain environments.                                                              | [Download](images/domain/vmware_create_domain_windows_10pro.zip)              |
| Windows Server 2019 Datacenter - Core               | blink-zero    | Domain      | Windows Server 2019 Datacenter       | Windows Server 2019 Datacenter Core VM for domain environments.                                         | [Download](images/domain/vmware_create_domain_windows_server2019dc_core.zip)    |
| Windows Server 2019 Datacenter - Desktop Experience | blink-zero    | Domain      | Windows Server 2019 Datacenter       | Windows Server 2019 Datacenter Desktop Experience VM for domain environments.                           | [Download](images/domain/vmware_create_domain_windows_server2019dc_de.zip) |
| Windows Server 2022 Datacenter - Core               | blink-zero    | Domain      | Windows Server 2022 Datacenter       | Windows Server 2022 Datacenter Core VM for domain environments.                                         | [Download](images/domain/vmware_create_domain_windows_server2022dc_core.zip)    |
| Windows Server 2022 Datacenter - Desktop Experience | blink-zero    | Domain      | Windows Server 2022 Datacenter       | Windows Server 2022 Datacenter Desktop Experience VM for domain environments.                           | [Download](images/domain/vmware_create_domain_windows_server2022dc_de.zip) |


### Community Images
**Currently: 3**

| Image Name                                          | Author        | Image Type  | OS                                   | Description                                                                                             | Download Link                                       |
|-----------------------------------------------------|---------------|-------------|--------------------------------------|---------------------------------------------------------------------------------------------------------|-----------------------------------------------------|
| Ubuntu 20.04 - OpenPLCv3                            | blink-zero    | Non-Domain  | Ubuntu 20.04                         | Minimal installation of Ubuntu 20.04 VM for non-domain environments with OpenPLC installed.             | [Download](images/community/vmware_create_linux_ubuntu20.04_openplcv3.zip) |
| Ubuntu 22.04 - Docker and Docker Compose            | blink-zero    | Non-Domain  | Ubuntu 22.04                         | Minimal installation of Ubuntu 22.04 VM for non-domain environments with Docker & Docker Compose installed.| [Download](images/community/vmware_create_linux_ubuntu22.04_docker.zip) |
| Windows 10 Pro - FactoryIO                          | blink-zero    | Non-Domain  | Windows 10 Professional              | Windows 10 Professional with FactoryIO and custom scene installed.                                      | [Download](images/community/vmware_create_windows_10pro_factoryio.zip) |

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
