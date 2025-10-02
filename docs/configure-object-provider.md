
# Configure Object Provider

## Goal 🎯

The goal of this file is to document the setup of the object providers for Central ATC.

## References 📝
- [Configuring Object Providers](https://help.sap.com/docs/ABAP_PLATFORM_NEW/ba879a6e2ea04d9bb94c7ccd7cdac446/f0507b09b1a64029a88ff994cae03aac.html?locale=en-US)

## Configure Object Provider 🛠️

### Create System Group
A system group subsumes multiple SAP systems (the productive system, the test system(s), and the development system(s)), which all represent a part of a system landscape of one and the same SAP release.

<img width="1101" height="338" alt="image" src="https://github.com/user-attachments/assets/a9d51828-6fa1-4112-89e8-547f91c1c850" />


| ID      | Description                              |
|---------|------------------------------------------|
| SG_SO_Solution_Manager  | SAP Solution Manager      |
| SG_CT_Central_Tooling | Central Tooling      |
| <system_group> | <description>        |
| <system_group> | <description>        |

#### Naming Convention
For a SAP ATC System Group, the naming convention should be a clear, descriptive ID and a short text description within the ATC administration settings.
> <SG>_<FIRST_TWO_LETTERS_OF_SYSTEMID>_<DESCRIPTION>
