# Windows Server Administration Lab - Admin Guide

## Project Overview

This project demonstrates practical Windows Server administration tasks in a lab environment.

The lab covers:

- Windows Server installation and configuration
- Active Directory Domain Services (AD DS)
- User and computer management
- DNS configuration
- DHCP configuration
- Group Policy management
- USB device blocking using Group Policy
- File and folder sharing
- HR department file permissions
- IT department file permissions
- IIS web server installation and configuration
- Testing and verification

## Lab Objectives

The main objectives of this lab are:

1. Configure a Windows Server environment.
2. Create and manage an Active Directory domain.
3. Create users and computers using Active Directory Users and Computers.
4. Configure DNS and DHCP services.
5. Apply Group Policy settings.
6. Configure secure file sharing and department-based permissions.
7. Install and configure IIS.
8. Verify that all configured services are working correctly.

## Server Administration

### Active Directory

Active Directory is used to centrally manage:

- Users
- Computers
- Groups
- Organizational Units
- Authentication and authorization

### DNS

DNS provides name resolution for the Windows Server domain environment.

### DHCP

DHCP automatically provides IP configuration to client computers, including:

- IP address
- Subnet mask
- Default gateway
- DNS server

### Group Policy

Group Policy is used to centrally manage security and configuration settings.

In this lab, a Group Policy is configured to block USB storage devices.

## File Sharing

Shared folders are configured on the Windows Server to provide controlled access to users and departments.

### HR File Permissions

HR users are provided access to the HR shared folder according to their assigned permissions.

### IT File Permissions

IT users are provided access to the IT shared folder according to their assigned permissions.

The permissions are configured to prevent unauthorized access between departments.

## IIS

Internet Information Services (IIS) is installed and configured as the web server.

IIS is verified by accessing the configured website from a client/browser.

## Testing and Verification

The following items are verified during testing:

- Active Directory functionality
- DNS name resolution
- DHCP IP assignment
- Group Policy application
- USB blocking policy
- File sharing
- HR folder permissions
- IT folder permissions
- IIS website accessibility

## Security Considerations

The lab follows basic administrative security practices:

- Use appropriate user permissions.
- Apply least-privilege access where possible.
- Separate departmental file permissions.
- Use Group Policy for centralized security configuration.
- Verify access controls after configuration.

## Troubleshooting

If a service does not work as expected:

1. Check the Windows Server service status.
2. Verify network connectivity.
3. Check DNS configuration.
4. Check DHCP scope and client IP configuration.
5. Run Group Policy update on the client.
6. Verify NTFS and share permissions.
7. Check IIS services and website configuration.
8. Review Windows Event Viewer for errors.

## Conclusion

This lab demonstrates essential Windows Server administration and infrastructure management skills, including Active Directory, DNS, DHCP, Group Policy, file sharing, permissions, and IIS.

The testing and verification steps confirm that the configured services and security controls are functioning as expected.
