---
title: Intelligent recap for Teams calls and meetings
ms.author: wlibebe
author: wlibebe
manager: pamgreen
ms.reviewer: weizxue, nijait
ms.date: 1/16/2024
ms.topic: how-to
ms.tgt.pltfrm: cloud
ms.service: msteams
audience: Admin
appliesto: 
  - Microsoft Teams
ms.localizationpriority: medium
search.appverid: MET150
f1.keywords:
- CSH
ms.custom: 
ms.collection: 
  - M365-collaboration
  - m365initiative-meetings
  - highpri
  - Tier1
  - m365initiative-voice
description: Learn how to manage Intelligent recap for Teams calls and meetings. Understand the licenses your users need to use intelligent recap for VoIP and PSTN calls.
---

# Intelligent recap for Teams calls and meetings

**APPLIES TO:** ![Image of a checkmark for yes](/office/media/icons/success-teams.png) Meetings ![Image of a checkmark for yes](/office/media/icons/success-teams.png) Calls

Intelligent recap for Microsoft Teams uses AI technology to improve your users’ productivity and efficiency. This article is designed to guide you, as an admin, in understanding intelligent recap’s prerequisites and capabilities.

To learn more about how your users use intelligent recap in their meetings, see [Meeting recap in Microsoft Teams](https://support.microsoft.com/office/meeting-recap-in-microsoft-teams-c2e3a0fe-504f-4b2c-bf85-504938f110ef#bkmk_intelligent_meeting_recap).

## Prerequisites

Intelligent recap is automatically available to users in your organization with the following required licenses and policies:

### Licensing

- You must assign your users a Microsoft 365 subscription that includes Teams or a Microsoft 365 (no Teams) subscription with a separate Teams license.
- You must assign a Teams Premium license or Microsoft 365 Copilot license to your users.
- For Public Switched Telephone Network (PSTN) calls, you must also assign a Teams Phone license and have a calling plan for your users. For information on Teams Phone licensing, see [Microsoft Teams add-on licenses](/microsoftteams/teams-add-on-licensing/microsoft-teams-add-on-licensing). To learn more about PSTN connectivity options, see [PSTN connectivity options](pstn-connectivity.md).

### Policies

#### Transcription

To allow your users to use intelligent recap, you must turn on transcription:

- PSTN, 1:1 peer-to-peer Voice over Internet Protocol (VoIP) calls: To turn on transcription, see [Configure call recording, transcription, and captions in Teams](call-recording-transcription-captions.md#enable-call-transcription).
- Meetings and group VoIP calls: To turn on transcription, see [Admins- Manage transcription and captions for Teams meetings](meeting-transcription-captions.md#transcription).

#### Recording

For the full recap experience for meetings, you must assign a policy that allows recording for your users. If recording is turned off, users experience recap without the recording, speakers, topics, and chapters. To turn on recording for meetings, see [Manage Teams recording policies for meetings and events](meeting-recording.md#allow-or-prevent-users-from-recording-meetings).

## Intelligent call recap

Intelligent call recap uses AI to allow your users to focus during their calls and save time on follow-ups.

### PSTN calls

PSTN calls are made and received using a phone number. Your users can access AI generated notes and recommended tasks for PSTN calls through the **Recap** button in the Calls app in Teams.

:::image type="content" source="media/i-recap-pstn-small.png" alt-text="Screenshot of intelligent call for PSTN calls in the Calls app." lightbox="media/i-recap-pstn-expand.png":::

### 1:1 peer-to-peer and group VoIP calls

1:1 peer-to-peer and group VoIP calls are made between Teams users. Your users can access AI generated notes, recommended tasks, speakers, topics, mentions, and chapters for 1:1 and group peer-to-peer calls through the **Recap** button in the call’s chat in Teams.

:::image type="content" source="media/intelligent-call-recap-small.png" alt-text="Screenshot of the intelligent call recap button in the call's chat." lightbox="media/intelligent-call-recap-expand.png":::

:::image type="content" source="media/intelligent-call-recap-2-small.png" alt-text="Screenshot of the intelligent call recap tab from the call's chat." lightbox="media/intelligent-call-recap-2-expand.png":::

## Intelligent meeting recap

Intelligent meeting recap uses AI to help your users focus on the meeting discussion instead of taking notes. This feature allows them to find key information, access highlights, and save time on follow-ups.

After the meeting ends, your users can access the following AI powered features for their meetings through the **Recap** tab in the Teams calendar and chat:

- AI meeting notes
- AI recommended tasks
- Personalized timeline markers show when users' names were mentioned, when screens were shared, and when they joined or left the meeting.
- Speaker timeline markers show who spoke during the meeting, when they spoke, and allows your users to jump to that moment.
- Meeting chapters divide the meeting into chapters, and meeting topics that allow your users to jump to a point in the meeting when a certain topic was discussed.

:::image type="content" source="media/new-i-recap-meetings-small.png" alt-text="Screenshot of intelligent meeting recap from the recap tab." lightbox="media/new-i-recap-meetings-expand.png":::

## Supported meetings and call types

Intelligent recap is supported on the following types of meetings and calls:

- Meetings: Meetings scheduled in the Teams client, meetings scheduled in Outlook, meet now
- Calls: PSTN, 1:1, group peer-to-peer

## Supported platforms

Intelligent recap is supported on the following platforms:

- Desktop
- Mobile

## Data and privacy

For details on data and privacy for intelligent recap, see [Data, privacy, and security for intelligent recap in Teams Premium](/microsoftteams/privacy/intelligent-recap).

## Related articles

- [Microsoft Teams Premium - Overview for admins](enhanced-teams-experience.md)
- [Configure call recording, transcription, and captions in Teams](call-recording-transcription-captions.md#enable-call-transcription)
- [Configure transcription and captions for Teams meetings](meeting-transcription-captions.md)
- [Plan for Teams meetings](plan-meetings.md)
- [Plan for Teams webinars](plan-webinars.md)
- [Plan for Teams town halls](plan-town-halls.md)
