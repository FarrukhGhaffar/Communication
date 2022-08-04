# ACS Rooms - Release History

## v1.0.0-beta.1 (2022-08-12)

This is the initial release of Rooms capability in Azure Communication Services in public preview. The following features are available

### Features available

* Create, Read, Update and Delete Rooms.
* Add, Remove users from the Room.
* Set schedule validity for room using ValidFrom and ValidTo parameters.
* Assign predefined roles to users in a room.
* Ability to conduct a VOIP call within a room with other ACS users
* Server events for CallStart, CallEnd, CallParticipantAdded, CallParticipantRemoved.
* Ability to control who joins a room using roomJoinPolicy to allow invited users only or to all users created under the ACS resource.

### Featuers not available.
* Interoperability with Teams
* Dialout to PSTN
* Dialin from PSTN user
* Chat
* Breakout rooms

### Onboarding
The SDK is released for the following platforms: arm64 and x86_64 (simulator)
<br/>Minimum supported iOS SDK version is 12.0
<br/>**BuildAzurePackages.sh script works only with Xcode 11.5 and above**
<br/>Please refer to the [Microsoft docs](https://docs.microsoft.com/en-us/azure/communication-services/quickstarts/voice-video-calling/getting-started-with-calling?pivots=platform-ios) of how to bootstrap a Calling sample application on iOS.
