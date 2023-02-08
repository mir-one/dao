# NFT TON DAO
NFT TON DAO is a collection of unique DAO on The Open Network. Each NFT for the participant, which confirms the information about  the DAO membership. Each time you participate in an DAO, TON DAO send a unique NFT, which is verified by a cryptographic record. These NFT are Non-Fungible Tokens and contain all information about the DAO.

## Usage
```
title                    // Title to display
image                    // 
description              // 
native_name              // 
native_name_lang         // 
english_name             // 
time                     // 
timezone                 // 
duration                 // duration|h=x|m=x|s=x or time interval|date1|date2|options
date                     // start date|YYY/|MM/DD or start and end dates|YYYY/MM/DD-YYYY/MM/DD
venue                    // 
location                 // 
coordinates              // coord|LAT|LON|region:XXXX_type:event|display=inline,title
type                     // 
theme                    // 
cause                    // 
motive                   // 
target                   // 
patron                   // or patrons
organisers               // or organizers
participants             // 
outcome                  // 
awards                   // 
url                      // 
blank_label              // or |blank_data
blank1_label             // or |blank1_data
blank2_label             // or |blank2_data
website                  // URL|example.com
notes                    // 
```
## Parameters
Parameter Templates

|Parameter|Required |Description | Type |Example |
|-|-|-|-|-|
|Name|yes|Name of the DAO|Text|DAO NFT|
|Image|None|Logo, logo or DAO icon|jpg,png,svg|
|Type|yes|For DAO: NFT DAO|text|NFT DAO|
|Consensus|no||||
|Current offer|No|Offer title|text||
||||| |
/ Number of members|none / Total number of DAO members. For two groups of circles, it is indicated in the form N1 + N2, where N1, N2 are the number of members of the first and second circles.|||
||||||
||||||
||||||
||||||
||||||
||||||
||||||
||||||
||||||
||||||
||||||
||||||
||||||
||||||
||||||
||||||
/ Address|none / DAO Account address / / EQBondcvD2_aOFADXSWJHs4ZazQDuEl9_wnvggpxi8hguofu|

## Example

```json
{
"name": "Build DAO Interdisciplinary Thinking",
"description": "Interdisciplinary Thinking DAO",
"image": "ipfs://CID/1.png",
"animation_url": "ipfs://CID/video.mp4",
"attributes": [
{
"trait_type": "Date",
"value": "2022/06/28"
},
{
"trait_type": "Time",
"value": "16:00"
},
{
"trait_type": "Location",
"value": "NGO Coworking center in CAO"
},
{
"trait_type": "DAO",
"value": "Interdisciplinary thinking"
},
{
"trait_type": "Delegation of proposals",
"value": "True"
},
{
"trait_type": "Fingerprint",
"value": "True"
},
{
"trait_type": "Consensus",
"value": "100%"
},
{
"trait_type": "Participants",
"value": "9"
},
{
"trait_type": "Expert network",
"value": "Yes"
},
{
"trait_type": "Target",
"value": "Build DAO Moon"
},
{
"trait_type": "Address",
"value": "Moscow, Koroviy Val str., 3, p. 5"
},
{
"trait_type": "Type",
"value": "Presentation"
},
{
            "trait_type": "Theme",
            "value": "Project Moon"
        },
        {
            "trait_type": "DAO Chat",
            "value": "https://t.me/+27ahbKRaHD44YTQy"
        }
    ]
}
```
