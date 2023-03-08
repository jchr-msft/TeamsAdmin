# TeamsAdmin

Sample scripts to help with the daily grind.
Most will require 'dot sourcing' ie
. .\<script>.ps1

then calling the powershell command.

First up is Get-TeamsEffectiveUserPolicy -UserID <userid> -Policy <policy> -ShowAll

ShowAll is optional, but shows all of the assignments and ranks of policies
Policy can be one of:
TeamsAppPermissionPolicy
TeamsAppSetupPolicy
TeamsAudioConferencingPolicy
TeamsCallParkPolicy
TeamsCallingPolicy
TenantDialPlan
TeamsEmergencyCallRoutingPolicy
TeamsEmergencyCallingPolicy
TeamsEnhancedEncryptionPolicy
TeamsMeetingPolicy
TeamsMessagingPolicy
TeamsUpdatePolicy
TeamsVoiceRoutingPolicy
TeamsVoicemailPolicy
