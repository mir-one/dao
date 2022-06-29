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
## Параметры
Шаблоны параметров

|Параметр|Обязятелен |Описание | Type |пример |
|-|-|-|-|-|
|название|да|Название DAO|Текст|DAO NFT|
|Изображение|нет|Эмблема, логотип или иконка DAO|jpg,png,svg|
|Тип|да|Для DAO: NFT DAO|текст|NFT DAO|
|Консенсус|нет||||
|текущее предложение|нет|Название предложения|текст||
||||||
|Количество членов|нет|Общее количество членов DAO. Для двух групп кругов указывается в виде N1 + N2, где N1, N2 — численность членов первого и второго круга.|||
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
|Адрес|нет|Адрес аккаунта DAO||EQBondcvD2_aOFADXSWJHs4ZazQDuEl9_wNvGGPxI8hGuOFU|

## Example

```json
{
    "name": "Build DAO Interdisciplinary Thinking",
    "description": "Interdisciplinary Thinking DAO",
    "image": "ipfs://CID/1.png",
    "animation_url": "ipfs://CID/video.mp4",
    "attributes": [
        {
            "trait_type": "Дата",
            "value": "2022/06/28"
        },
        {
            "trait_type": "Время",
            "value": "16:00"
        },
        {
            "trait_type": "Место",
            "value": "Коворкинг-центр НКО в ЦАО"
        },
        {
            "trait_type": "DAO",
            "value": "Междисциплинарное мышление"
        },
        {
            "trait_type": "Делегирование предложений",
            "value": "Да"
        },
        {
            "trait_type": "Отпечаток",
            "value": "Да"
        },
        {
            "trait_type": "Конcенсус",
            "value": "100%"
        },
        {
            "trait_type": "Участники",
            "value": "9"
        },
        {
            "trait_type": "Экспертная сеть",
            "value": "Да"
        },
        {
            "trait_type": "Цель",
            "value": "Сборка DAO Луна"
        },
        {
            "trait_type": "Адрес",
            "value": "Москва, ул. Коровий Вал, 3, стр. 5"
        },
        {
            "trait_type": "Тип",
            "value": "Презентация"
        },
        {
            "trait_type": "Тема",
            "value": "Проект Луна"
        },
        {
            "trait_type": "DAO Chat",
            "value": "https://t.me/+27ahbKRaHD44YTQy"
        }
    ]
}
```