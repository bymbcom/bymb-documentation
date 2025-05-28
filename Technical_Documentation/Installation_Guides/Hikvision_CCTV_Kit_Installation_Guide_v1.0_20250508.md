# Hikvision CCTV Kit Installation Guide

## Document Information
- **Document ID:** Technical_InstallationGuide_HikvisionCCTVKit_v1.0_20250508
- **Author:** BY MB Technical Team
- **Last Updated:** May 8, 2025
- **Version:** 1.0
- **Language:** English
- **Review Date:** August 8, 2025
- **Keywords:** CCTV installation, Hikvision, NVR setup, security cameras, IP cameras, PoE, network video recorder, camera mounting, network configuration

## Overview
[AI-PRIORITY]

This installation guide provides step-by-step instructions for setting up Hikvision CCTV kits offered by BY MB Consultancy. The guide covers both the 4MP and 6MP Bullet/Dome kit configurations and includes all aspects of the installation process from initial planning through to final system configuration and testing.

While BY MB Consultancy provides professional installation services for all CCTV kit purchases, this guide serves as a comprehensive reference for:
- Technical staff performing installations
- Maintenance personnel troubleshooting existing systems
- Advanced customers who wish to understand their system in greater detail

**Applicable Products:**
- Hikvision 4MP Bullet/Dome CCTV PoE Kit
- Hikvision 6MP Bullet/Dome CCTV PoE Kit
- Hikvision Video Intercom Kit (optional add-on)

## Safety Precautions
[AI-CAUTION]

Before beginning the installation, ensure all safety protocols are followed:

- **Electrical Safety:**
  - Turn off power to the installation area at the circuit breaker before running cables
  - Use appropriate electrical insulation tools when working near power sources
  - Verify all connections are secure before powering on equipment
  - Never install equipment in wet locations without proper weatherproofing

- **Physical Safety:**
  - Use appropriate ladders or elevated platforms for ceiling and wall-mounted installations
  - Wear safety goggles when drilling into walls, ceilings, or other surfaces
  - Wear gloves when handling rough-edged equipment or mounting brackets
  - Be aware of and avoid electrical wiring, plumbing, and gas lines in walls and ceilings

- **Equipment Protection:**
  - Handle all electronic components with care to prevent static discharge damage
  - Keep components in anti-static packaging until ready for installation
  - Protect equipment from dust and debris during the installation process
  - Avoid exposing equipment to extreme temperatures or moisture

- **Data Security:**
  - Change all default passwords immediately upon installation
  - Document all passwords in a secure manner and provide to the client
  - Ensure network configurations follow security best practices
  - Verify firmware is updated to the latest stable version

## Pre-Installation Planning
[AI-PRIORITY]

### Site Assessment

1. **Coverage Area Determination:**
   - Walk through the property with client to identify critical monitoring areas
   - Note entry/exit points requiring surveillance
   - Identify valuable assets or areas of concern
   - Consider lighting conditions at different times of day

2. **Camera Placement Planning:**
   - Select optimal mounting locations for maximum coverage
   - Consider the following factors for each camera:
     - Field of view requirements
     - Lighting conditions (avoid direct sunlight and backlight)
     - Weather exposure for outdoor cameras
     - Height placement (typically 2.5-3 meters for optimal angle)
     - Potential vandalism or tampering access
   - Document proposed camera locations on property floor plan
   - Confirm locations with client before proceeding

3. **NVR Location Selection:**
   - Identify a secure, dust-free location with adequate ventilation
   - Ensure proximity to power source and network router
   - Consider accessibility for maintenance while maintaining security
   - Verify ambient temperature remains within operational range (10-35°C)

4. **Network Assessment:**
   - Evaluate existing network infrastructure
   - Document wireless coverage areas if using wireless cameras
   - Identify available network ports on router/switch
   - Verify internet connection speed for remote viewing capabilities
   - Document IP addressing scheme and available addresses

### Equipment Verification

1. **Kit Contents Checklist:**
   - 2 × Bullet Cameras (4MP or 6MP depending on kit)
   - 2 × Dome Cameras (4MP or 6MP depending on kit)
   - 1 × 4-Channel Network Video Recorder (NVR)
   - 1 × 1TB Western Digital Hard Drive (pre-installed)
   - 5 × Network Cables
   - 1 × HDMI Cable
   - Mounting hardware (screws, wall anchors)
   - Power adapters and cables

2. **Additional Required Tools (Installer Provided):**
   - Electric drill with masonry and wood bits
   - Screwdriver set (Phillips and flathead)
   - Wire stripper/cutter
   - Ethernet cable crimping tool (if custom cable lengths required)
   - Cable tester
   - Measuring tape
   - Level
   - Ladder or step stool
   - Fish tape for pulling cables
   - Flashlight or headlamp
   - Multimeter for power testing
   - Cable management supplies (clips, ties, conduit)

3. **Optional Equipment:**
   - Additional network cables if included lengths are insufficient
   - Weatherproof junction boxes for outdoor connections
   - Conduit for protecting outdoor cables
   - Surge protectors for equipment
   - Network switch if additional PoE ports are needed
   - Monitor for NVR configuration (if client doesn't have HDMI display)

## Installation Process
[AI-EXAMPLE]

### Step 1: NVR Setup and Configuration

1. **Physical NVR Installation:**
   - Place NVR in designated location with adequate ventilation
   - Connect HDMI cable from NVR to monitor/TV
   - **Do not connect power yet**

2. **Hard Drive Verification:**
   - Confirm HDD is properly installed (pre-installed in kits)
   - If replacing/upgrading HDD:
     - Disconnect power completely
     - Remove NVR cover according to manufacturer instructions
     - Connect SATA data and power cables to HDD
     - Secure HDD with provided screws
     - Replace NVR cover

3. **Initial Power-Up:**
   - Connect NVR power adapter to outlet
   - Power on the NVR using the rear switch or button
   - Verify front panel LEDs illuminate
   - Confirm video output appears on connected monitor

4. **Initial NVR Configuration:**
   - Follow on-screen setup wizard
   - Set administrative password (document securely)
   - Configure time and date settings
   - Select appropriate language
   - Set timezone to Arabian Standard Time (AST, UTC+3)
   - Do not configure network settings yet

### Step 2: Camera Mounting and Installation

1. **Preparation for Each Camera:**
   - Verify power before mounting using PoE injector or power adapter
   - Confirm camera functions properly before permanent installation
   - Test video signal using temporary connection to NVR

2. **Bullet Camera Installation:**
   - Mark mounting holes using bracket as template
   - Drill appropriate sized holes for surface material
   - Insert wall anchors if mounting on masonry/concrete
   - Feed cable through bracket or wall if using concealed wiring
   - Secure bracket to wall with provided screws
   - Attach camera to bracket and adjust to desired angle
   - Tighten all adjustment screws firmly
   - Apply weatherproof sealant around cable entry points for outdoor installations

3. **Dome Camera Installation:**
   - Mark mounting holes using camera base as template
   - Drill appropriate sized holes for surface material
   - Insert wall anchors if mounting on masonry/concrete
   - Feed cable through ceiling/wall if using concealed wiring
   - Secure dome base to surface with provided screws
   - Connect cabling to camera
   - Attach dome cover and ensure it is securely fastened
   - Adjust camera angle as needed before finalizing dome position

4. **Cable Management:**
   - Run cables along baseboards, crown molding, or within walls where possible
   - Use cable management clips or conduit to secure exposed cables
   - Maintain minimum 12-inch separation from high-voltage electrical lines
   - Label both ends of each cable with camera location
   - Leave service loop of extra cable at camera end for future adjustments
   - Use outdoor-rated conduit for external cable runs
   - Seal all outdoor penetrations with appropriate weatherproof material

### Step 3: Network and Power Connections

1. **PoE Connections:**
   - Connect each camera's Ethernet cable to corresponding PoE port on NVR
   - Verify power LED illuminates on each camera
   - PoE Ports on NVR are typically labeled 1-4, matching the channel numbers

2. **Network Connection:**
   - Connect NVR to router/network using the LAN port (non-PoE port)
   - Verify network activity LEDs illuminate on NVR and router

3. **Cable Verification:**
   - Test each network connection using cable tester or by checking NVR status
   - Ensure all connections are secure
   - Verify each camera has power and is recognized by the NVR

4. **Connection Troubleshooting:**
   - If camera not powered: check PoE connection, try different port
   - If camera powered but no video: verify cable integrity, check camera settings
   - If network connection fails: verify cable, router settings, and NVR configuration

### Step 4: NVR System Configuration

1. **Network Setup:**
   - Configure NVR network settings:
     - Set to DHCP for automatic IP assignment (recommended for most installations)
     - Alternatively, configure static IP if required by client network
     - Document assigned IP address
   - Test network connectivity by pinging router or internet
   - Verify remote access capability through LAN

2. **Camera Activation and Configuration:**
   - Access camera management menu on NVR
   - All connected cameras should be automatically detected
   - If cameras are not detected:
     - Verify physical connections
     - Check for IP address conflicts
     - Ensure cameras are Hikvision compatible
   - Activate each camera with secure password
   - Rename cameras based on location (Front Door, Backyard, etc.)

3. **Recording Configuration:**
   - Set recording schedule (typically continuous or motion detection)
   - Configure motion detection sensitivity for each camera
   - Set pre-record and post-record durations (recommend 5-10 seconds)
   - Configure recording quality:
     - Mainstream: H.265+ encoding at full resolution (4MP/6MP)
     - Substream: Lower resolution for remote viewing (recommend 720p)
   - Calculate and verify storage duration based on settings

4. **Storage Management:**
   - Format HDD through NVR interface
   - Set storage quotas if applicable
   - Configure overwrite settings (typically enabled)
   - Enable S.M.A.R.T monitoring for drive health

### Step 5: Remote Access Setup

1. **Hik-Connect Service Configuration:**
   - Enable Hik-Connect service in NVR menu
   - Register device using serial number or QR code
   - Verify cloud connectivity status shows "Connected"
   - Add device to Hik-Connect account (create if necessary)
   - Verify remote access through mobile app

2. **Mobile App Setup:**
   - Install Hik-Connect app on client's mobile device
   - Log in using created account credentials
   - Add NVR using QR code scan or manual entry
   - Verify live view functionality for all cameras
   - Test playback and configuration capabilities
   - Demonstrate notification settings for motion events

3. **Port Forwarding (if required):**
   - If direct remote access is needed (beyond Hik-Connect):
     - Identify NVR's HTTP port (default 80) and server port (default 8000)
     - Access router configuration page
     - Create port forwarding rules for both ports to NVR's IP address
     - Test remote access using public IP address

4. **DDNS Setup (if required):**
   - If static public IP is not available:
     - Configure DDNS service in NVR
     - Select service provider (HiDDNS recommended)
     - Create domain name and verify registration
     - Test remote access using domain name

### Step 6: System Testing and Verification

1. **Camera View Optimization:**
   - Fine-tune each camera's position for optimal coverage
   - Adjust focus and zoom settings if available
   - Test under various lighting conditions
   - Verify night vision operation in low-light conditions
   - Confirm motion detection triggering for each camera

2. **Recording Verification:**
   - Trigger test recordings for each camera
   - Verify recorded footage quality and frame rate
   - Test motion detection recording
   - Ensure pre-record and post-record function properly
   - Verify recording retention period

3. **Remote Access Validation:**
   - Test remote viewing from multiple devices
   - Verify live view, playback, and configuration access
   - Test motion alert notifications
   - Ensure bandwidth usage is appropriate for client's internet connection

4. **System Integration Testing:**
   - If additional systems are connected (Video Intercom, Alarm, etc.):
     - Verify integration functionality
     - Test triggered recordings from external events
     - Confirm alert notifications function as expected

## Video Intercom Kit Installation (Optional Add-On)
[AI-PRIORITY]

If the client has also purchased the Hikvision Video Intercom Kit as an add-on to their CCTV system, follow these additional steps:

### Step 1: Door Station Installation

1. **Mounting Location Selection:**
   - Position at appropriate height (typically 1.4-1.6 meters from ground)
   - Ensure protection from direct rain and sunlight
   - Verify adequate lighting for night operation
   - Consider angle for camera viewing of visitors

2. **Physical Installation:**
   - Mount the included surface mounting box at selected location
   - Run Ethernet cable to the mounting location
   - Connect Ethernet cable to door station
   - Secure door station to mounting box
   - Apply weather sealant around edges if exposed to elements

3. **Wiring for Access Control (if applicable):**
   - Connect electric lock control wires to door station terminals
   - Follow lock manufacturer's specifications for NC/NO connections
   - Install and connect exit button if required

### Step 2: Indoor Station Installation

1. **Mounting Location Selection:**
   - Position at convenient height in central location (typically 1.4-1.6 meters)
   - Ensure accessibility for all household members
   - Avoid locations with high moisture or heat
   - Consider proximity to network switch or router

2. **Physical Installation:**
   - Mark mounting holes using bracket as template
   - Drill appropriate sized holes for surface material
   - Insert wall anchors if mounting on masonry/concrete
   - Run Ethernet cable to the mounting location
   - Secure mounting bracket to wall with provided screws
   - Connect Ethernet cable to indoor station
   - Attach indoor station to mounting bracket

### Step 3: Network Configuration

1. **PoE Switch Setup:**
   - Connect the included 4-port PoE switch to power
   - Connect door station and indoor station to PoE ports
   - Connect PoE switch to network router or main switch

2. **Intercom Activation:**
   - Power on all devices
   - Wait for the indoor station to initialize
   - Follow on-screen activation wizard
   - Set administration password
   - Configure network settings (DHCP recommended)

3. **Device Association:**
   - Access the indoor station configuration menu
   - Add door station to the system
   - Verify communication between stations
   - Test call function from door to indoor station

### Step 4: Integration with CCTV System

1. **Network Integration:**
   - Ensure intercom system and CCTV NVR are on same network
   - Configure any VLANs or network segmentation if applicable

2. **Hik-Connect Integration:**
   - Add intercom devices to same Hik-Connect account as CCTV
   - Verify all devices appear in mobile app
   - Configure appropriate permissions for users

3. **Testing Integrated Functions:**
   - Test door release function
   - Verify video and audio quality
   - Test call functionality and notifications
   - Confirm integration with CCTV recording if configured

## Post-Installation

### System Handover

1. **Client Training Session:**
   - Demonstrate system operation including:
     - Live view access
     - Playback and video export
     - Mobile app usage
     - Basic troubleshooting
   - Provide written instructions for common operations
   - Answer all client questions

2. **Documentation Handover:**
   - Provide system diagram showing camera locations
   - Document all passwords (in secure manner)
   - Include manufacturer's manuals and quick guides
   - Provide BY MB Consultancy contact information for support
   - Include warranty information and service schedule

3. **Final Verification:**
   - Walk through the installation with client
   - Confirm all cameras are positioned as agreed
   - Verify client can operate system independently
   - Address any immediate concerns or questions

### Maintenance Recommendations

1. **Regular Maintenance Schedule:**
   - Quarterly visual inspection of all cameras
   - Semi-annual cleaning of camera lenses and housings
   - Annual system performance review
   - Regular firmware updates as released

2. **Client Maintenance Tasks:**
   - Regular monitoring of system status
   - Periodic video quality checks
   - Reporting any issues promptly
   - Keeping system area clean and ventilated

3. **BY MB Consultancy Support:**
   - 24/7 technical support availability
   - Warranty service for 2 years on all components
   - Extended warranty options available
   - Professional maintenance service packages

## Troubleshooting Guide
[AI-EXAMPLE]

### Camera Issues

| Problem | Possible Causes | Solutions |
|---------|----------------|-----------|
| No video from camera | - No power to camera<br>- Damaged cable<br>- Incorrect port connection | 1. Check PoE connection and LED indicators<br>2. Test cable with cable tester<br>3. Try connecting to different NVR port<br>4. Verify camera activation status in NVR |
| Blurry image | - Dirty lens<br>- Lens out of focus<br>- Moisture in housing | 1. Clean lens with microfiber cloth<br>2. Adjust focus (varies by model)<br>3. Check for housing seal integrity<br>4. Replace desiccant in camera housing if applicable |
| Poor night vision | - IR LEDs not functioning<br>- Reflective surface in view<br>- Incorrect camera settings | 1. Verify IR LEDs illuminate in dark conditions<br>2. Reposition camera away from reflective surfaces<br>3. Check day/night settings in camera configuration<br>4. Adjust IR intensity if applicable |
| Intermittent video loss | - Network interference<br>- Power fluctuations<br>- Cable damage | 1. Check cable routing away from interference sources<br>2. Test power stability with multimeter<br>3. Replace cable if intermittent connection detected<br>4. Verify switch/NVR port functionality |

### NVR Issues

| Problem | Possible Causes | Solutions |
|---------|----------------|-----------|
| NVR not powering on | - Power adapter failure<br>- Power outlet issues<br>- Internal NVR failure | 1. Test outlet with known working device<br>2. Verify power adapter output with multimeter<br>3. Check for loose connections<br>4. Test with replacement power adapter |
| NVR not recording | - Hard drive not detected<br>- Recording schedule misconfigured<br>- Hard drive full<br>- Hard drive failure | 1. Check HDD status in storage management<br>2. Verify recording schedule is properly configured<br>3. Enable disk overwrite if disabled<br>4. Run disk health check; replace if failing |
| Cannot access NVR remotely | - Network connection issue<br>- Hik-Connect not configured<br>- Port forwarding issues<br>- Incorrect login credentials | 1. Verify NVR is connected to network<br>2. Check Hik-Connect status shows "Connected"<br>3. Verify port forwarding configuration<br>4. Test login credentials locally first |
| NVR freezing or rebooting | - Overheating<br>- Power instability<br>- Firmware issues<br>- Hard drive problems | 1. Check ventilation and ambient temperature<br>2. Install UPS for power conditioning<br>3. Update firmware to latest version<br>4. Test HDD and replace if necessary |

### Network Issues

| Problem | Possible Causes | Solutions |
|---------|----------------|-----------|
| IP address conflict | - Static IP conflicts<br>- DHCP reservation issues | 1. Switch to DHCP temporarily<br>2. Verify IP address assignments in router<br>3. Configure DHCP reservations for all devices<br>4. Document IP addressing scheme |
| Slow remote viewing | - Insufficient upload bandwidth<br>- Substream not configured<br>- Network congestion | 1. Test internet upload speed<br>2. Configure substream for remote viewing<br>3. Adjust bitrate settings<br>4. Consider bandwidth limiting during business hours |
| Cameras disconnecting | - PoE budget exceeded<br>- Network switch issues<br>- Camera compatibility | 1. Calculate total PoE power requirements<br>2. Power cycle PoE switch<br>3. Verify switch configuration<br>4. Consider additional or higher capacity PoE switch |
| Mobile app connection issues | - App outdated<br>- Device registration problems<br>- Account issues | 1. Update Hik-Connect app to latest version<br>2. Verify device is properly registered<br>3. Check account status and permissions<br>4. Re-add device to account |

## Escalation Procedure
[AI-ESCALATE]

If the installation cannot be completed successfully or if you encounter issues that cannot be resolved using the troubleshooting guide, follow this escalation procedure:

### Level 1: On-site Resolution
1. Contact Technical Support for remote assistance
   - +973-66300033 (Option 2)
   - Provide system details and specific issue description
   - Follow remote guidance to attempt resolution
   - Document all troubleshooting steps attempted

### Level 2: Technical Specialist Support
If Level 1 support cannot resolve the issue:
1. Request escalation to Level 2 Technical Specialist
2. Specialist will either:
   - Provide advanced remote guidance
   - Schedule on-site visit for complex issues
   - Authorize equipment replacement if necessary

### Level 3: Engineering Support
For critical system failures or complex integration issues:
1. Technical specialist will escalate to Engineering team
2. Engineering will evaluate:
   - System design appropriateness
   - Environmental factors affecting performance
   - Compatibility issues between components
   - Potential for alternative solutions

### Emergency Support
For urgent situations affecting critical security operations:
1. Call emergency line: +973-66300033 (Option 0)
2. Available 24/7 including weekends and holidays
3. Provide site location and nature of emergency
4. On-call technician will respond within 60 minutes

## Related Documents
- Hikvision NVR User Manual
- Hikvision Camera Configuration Guide
- Network Video Recorder Configuration Best Practices
- Camera Placement Optimization Guide
- Hik-Connect Mobile App User Guide
- Video Intercom User Guide
- BY MB Consultancy Support Service Level Agreement
- Warranty and Maintenance Policy

## Version History
| Version | Date | Changes | Author |
|---------|------|---------|--------|
| 1.0 | 2025-05-08 | Initial document creation | BY MB Technical Team |