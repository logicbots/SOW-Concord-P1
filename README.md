# Statement of Work - MDA Machine

A document prepared by 
Logicbots on 20th November 2022

## Table of Content

* Executive Summary
* Delivery Scope
* Device APIs
* Devices
* Maintenance
* Exclusions
* Deliverables
* Investment and Cost
* Customer Responsibilities
* Acceptance Criteria
* Assumptions


## Executive Summary
This documentation is to serve as a 'Statement of Work' or SOW for designing & developing an Microdermabrasion(MDA) system to enhance and empower dermatologist. The advancement in the field of IoT, Networks, Computing and Data Science has made possible Integrated systems that can help businesses. Such a system would include a means to capture, catalogue and analyze data, along with tools to enforce 'business logic'.

Logicbots will work with Concord Medisys to:

* Develop edge device firmware.
* Designing the PCB. 
* Develop and Engineer the system.
* Provide documentation of the new system.
* Knowledge Transfer/Integration with Concord Medisys.

Logicbots proposes to design, develop v1.0 of the proposed system to Concord Medisys.

The Value Proposition of using Logicbots for this project are:
* Proven engineering techniques for making Integrated systems.
* Leveraging our experience in working with IoT toolkit (ESP/ARDUINO/RPI) to bootstrap your effort. 
* Using subject matter experts to complete the project quickly. Rapid project completion minimizes disruptions and allows organizations to realize cost-saving quickly.

## Delivery Scope

* Project Definition
    - A review of the current system which helps in the firmware & design developing of the devices.
    - A project kickoff meeting to discuss and document the complete scope of this system and the goals and requirements of this project.

## Device APIs

* Admin SDK / APIs to interact with the device for setting -
    - Machine Timer, getting pwm for UI and other device controlling APIs. 
## Devices

* Data to Capture from Devices

```
RPI W:               Main component which works as a CPU.  

Vaccum regulator:    For maintaining desired amount of suction.

L298 :               Motor driver for controlling regulator.

Power Supply:        12V 5Amp supply.

LED:                 Addressable LEDs which have a total of 16 million colour combination.

LCD:                 7 inch LCD panel for user interface.
```


## Maintenance (if required)
The period after the development for maintaining the product to be discussed with Concord Medisys as it incurred extra charges.

## Exclusions
The followings are excluded from the project scope
* The packages used and maintained by Logicbots for interfacing with IoT Devices.

## Deliverables

Main high level tasks are given below - 

1. Designing & Developing the device firmware which include standalone GUI from which user can able to view device details and control the device.

2. Development of GUI which contains 4-5 pages. Deployment will be done locally on RPI.

3. Integration of GUI with hardware to ensure seamless connectivity.

4. Creating Schematics and providing gerbers for main board and led panel PCB.

5. Software Access - top-level Git repositories for the hardware SDKs and APIs.

6. Documentation for the proposed changes in the system.

## Investment and Cost (To be discussed)
#### Phase - 1

* Man-hour required: 15 days ( Sensor delivery time not included )

* Hardware required & Sourcing Cost: TBD

 * Payment Schedule

| Milestone                                                      | Percentage    | Amount | 
| -------------                                                  |:-------------:| -----: |  
| First working prototypes                                       | 40%           | (Hardware cost if any) + 15000 |
| Second working prototypes                                      | 80%           | 10000  |
| Software handover + Documentation                              | 100%          | 10000   |

#### *Milestone should be funded in advance.

## Customer Responsibilities
* The nature of this engagement dictates that Logicbots receive a frequent and enthusiastic response from the appropriate personnel.
* A weekly review between the Logicbots and Concord Medisys or his designate will ensure that the expectations of this engagement are met.
* Concord Medisys will assign a key contact who will be responsible for providing Logicbots with information, access to personnel, and facility access if required.
* Concord Medisys will provide a work area space with desk, chair, Internet access for use by Logicbots to conduct project business while working on-site.

## Acceptance Criteria
After this evaluation, all deliverables for this phase will be presented to Concord Medisys for review.

Concord Medisys or his representative will have Seven business days from the date of delivery of any document that is a deliverable to review it and request any changes. If Logicbots does not receive notification of any required changes within this period, the document will be deemed to have been accepted without modification and will be reissued as a final copy.

If Logicbots is notified by Concord Medisys, within the above time frame, of any changes required, Logicbots will within two business days of such notification implement those changes as have been agreed between the parties.  A final copy of the document will then be submitted to Concord Medisys.

## Assumptions
* General
    * All documentation created for this project will be available in hard copy and electronic format.
    * Any modifications to the scope of work will be handled through a change control process and will be agreed to by both parties.

* Commercial
    * Additional costs may be incurred where any delay not under the control of Logicbots that causes his personnel to not fulfil their scheduled tasks.
    * Concord Medisys will be available at the time of completion of the build phase so that all documentation can be accepted and signed.
    * Additional costs may be incurred where any work scheduled to be undertaken by Logicbots is postponed by Concord Medisys after 24 hours of its commencement.
    * All changes to the schedule or technical requirements must be provided to Logicbots in written format. Email is included as written format. Receipt of all correspondence should be confirmed by phone wherever possible.
    * Concord Medisys has accepted the costs/times estimate as detailed in this document
    * Concord Medisys has accepted the Logicbots standard terms and conditions mentioned above.


## Approved by
Name:   
Date:   
Position: 
