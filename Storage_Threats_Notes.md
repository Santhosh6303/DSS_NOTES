
# Storage Level Threats and Vulnerabilities

## Storage Area Network (SAN)
- **SANs**: Network architecture providing large amounts of storage access to many servers.
- **Storage Security**: Protects data residing in the SAN from unauthorized access.
- **Why Storage Security?**: Assumptions about IP security shouldn't neglect the Fibre Channel (FC).
- **Connectivity**: SANs bridge various security zones (DMZ, Internal, App, Database).

## Importance of SAN Security
- **Key Concepts**:
  - **Authentication**: Verifies identity to ensure authorized access.
  - **Authorization**: Grants appropriate levels of access to users.
  - **Encryption**: Protects data in transit or at rest.

## Fibre Channel Overview
- **Fibre Channel**: A high-speed data transfer technology (up to 2Gbps) replacing SCSI.
  - **HBA**: Host Bus Adapter (Network Interface Card for Fibre Channel).
  - **LUNs**: Logical Unit Numbers, subdivisions of storage within SAN.
  - **WWN**: World Wide Name, MAC-like address for HBAs.
  - **Zoning**: Logical segmentation of Fibre Channel nodes.
  
### FC Layers
- **FC-0**: Physical Layer (optical fiber, connectors).
- **FC-1**: Encoding/Decoding and error control.
- **FC-2**: Signaling/Framing layer, transport mechanism.
- **FC-3**: Common services layer, advanced features (striping, hunt groups).
- **FC-4**: Application interfaces layer for network and channel data.

## Attacks on Fibre Channel SANs
### HBA Attacks
- **Spoofing**: Changing WWNs to gain unauthorized access to LUNs.
  
### LUN Masking Attacks
- **LUN Masking**: Hides/reveals parts of storage disks, not originally for security.
- **Attack**: Remove masking on client node to access all LUNs.

### Switch Attacks
- **Switch Zoning**: Grants/denies access based on WWNs or port numbers.
- **Zone Hopping**: Spoof WWN or discover routes to gain unauthorized access.

### Frame Attacks
- **Session Hijacking**: Predicting sequence IDs in FC frames to take control of a session.
