{
  "info": {
    "name": "Kaltura VPaaS Get Service Contentdistribution Entrydistribution Action Valate",
    "_postman_id": "9a85cbff-6101-450e-8f85-fc01008665f2",
    "description": "Validates Entry Distribution by id for submission",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "4ef4c146-d32a-40eb-90bd-30618a2f3cb9",
          "name": "attachmentAsset.setContent",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attachment_attachmentasset/action/setContent?contentResource[assetId]=%7B%7D&contentResource[content]=%7B%7D&contentResource[dropFolderFileId]=%7B%7D&contentResource[entryId]=%7B%7D&contentResource[fileSyncObjectType]=%7B%7D&contentResource[flavorParamsId]=%7B%7D&contentResource[forceAsyncDownload]=%7B%7D&contentResource[keepOriginalFile]=%7B%7D&contentResource[keyPassphrase]=%7B%7D&contentResource[localFilePath]=%7B%7D&contentResource[objectId]=%7B%7D&contentResource[objectSubType]=%7B%7D&contentResource[objectType]=%7B%7D&contentResource[privateKey]=%7B%7D&contentResource[publicKey]=%7B%7D&contentResource[resources]=%7B%7D&contentResource[resource][assetId]=%7B%7D&contentResource[resource][content]=%7B%7D&contentResource[resource][dropFolderFileId]=%7B%7D&contentResource[resource][entryId]=%7B%7D&contentResource[resource][fileSyncObjectType]=%7B%7D&contentResource[resource][flavorParamsId]=%7B%7D&contentResource[resource][forceAsyncDownload]=%7B%7D&contentResource[resource][keepOriginalFile]=%7B%7D&contentResource[resource][keyPassphrase]=%7B%7D&contentResource[resource][localFilePath]=%7B%7D&contentResource[resource][objectId]=%7B%7D&contentResource[resource][objectSubType]=%7B%7D&contentResource[resource][objectType]=%7B%7D&contentResource[resource][privateKey]=%7B%7D&contentResource[resource][publicKey]=%7B%7D&contentResource[resource][resources]=%7B%7D&contentResource[resource][resource][assetId]=%7B%7D&contentResource[resource][resource][content]=%7B%7D&contentResource[resource][resource][dropFolderFileId]=%7B%7D&contentResource[resource][resource][entryId]=%7B%7D&contentResource[resource][resource][fileSyncObjectType]=%7B%7D&contentResource[resource][resource][flavorParamsId]=%7B%7D&contentResource[resource][resource][forceAsyncDownload]=%7B%7D&contentResource[resource][resource][keepOriginalFile]=%7B%7D&contentResource[resource][resource][keyPassphrase]=%7B%7D&contentResource[resource][resource][localFilePath]=%7B%7D&contentResource[resource][resource][objectId]=%7B%7D&contentResource[resource][resource][objectSubType]=%7B%7D&contentResource[resource][resource][objectType]=%7B%7D&contentResource[resource][resource][privateKey]=%7B%7D&contentResource[resource][resource][publicKey]=%7B%7D&contentResource[resource][resource][resources]=%7B%7D&contentResource[resource][resource][resource][assetId]=%7B%7D&contentResource[resource][resource][resource][content]=%7B%7D&contentResource[resource][resource][resource][dropFolderFileId]=%7B%7D&contentResource[resource][resource][resource][entryId]=%7B%7D&contentResource[resource][resource][resource][fileSyncObjectType]=%7B%7D&contentResource[resource][resource][resource][flavorParamsId]=%7B%7D&contentResource[resource][resource][resource][forceAsyncDownload]=%7B%7D&contentResource[resource][resource][resource][keepOriginalFile]=%7B%7D&contentResource[resource][resource][resource][keyPassphrase]=%7B%7D&contentResource[resource][resource][resource][localFilePath]=%7B%7D&contentResource[resource][resource][resource][objectId]=%7B%7D&contentResource[resource][resource][resource][objectSubType]=%7B%7D&contentResource[resource][resource][resource][objectType]=%7B%7D&contentResource[resource][resource][resource][privateKey]=%7B%7D&contentResource[resource][resource][resource][publicKey]=%7B%7D&contentResource[resource][resource][resource][resources]=%7B%7D&contentResource[resource][resource][resource][storageProfileId]=%7B%7D&contentResource[resource][resource][resource][token]=%7B%7D&contentResource[resource][resource][resource][url]=%7B%7D&contentResource[resource][resource][resource][version]=%7B%7D&contentResource[resource][resource][storageProfileId]=%7B%7D&contentResource[resource][resource][token]=%7B%7D&contentResource[resource][resource][url]=%7B%7D&contentResource[resource][resource][version]=%7B%7D&contentResource[resource][storageProfileId]=%7B%7D&contentResource[resource][token]=%7B%7D&contentResource[resource][url]=%7B%7D&contentResource[resource][version]=%7B%7D&contentResource[storageProfileId]=%7B%7D&contentResource[token]=%7B%7D&contentResource[url]=%7B%7D&contentResource[version]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "contentResource[fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "contentResource[resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "contentResource[resource][resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "contentResource[resource][resource][resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                }
              ]
            },
            "description": "Update content of attachment asset"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "65c8708a-13be-4de9-8cf4-1e2a09f6694d"
            }
          ]
        },
        {
          "id": "c827f9f4-da17-43f3-a6ff-d3ab00e53b0c",
          "name": "baseEntry.addContent",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/baseentry/action/addContent?entryId=%7B%7D&No Name=%7B%7D&resource[assetId]=%7B%7D&resource[content]=%7B%7D&resource[dropFolderFileId]=%7B%7D&resource[entryId]=%7B%7D&resource[fileSyncObjectType]=%7B%7D&resource[flavorParamsId]=%7B%7D&resource[forceAsyncDownload]=%7B%7D&resource[keepOriginalFile]=%7B%7D&resource[keyPassphrase]=%7B%7D&resource[localFilePath]=%7B%7D&resource[objectId]=%7B%7D&resource[objectSubType]=%7B%7D&resource[objectType]=%7B%7D&resource[privateKey]=%7B%7D&resource[publicKey]=%7B%7D&resource[resources]=%7B%7D&resource[resource][assetId]=%7B%7D&resource[resource][content]=%7B%7D&resource[resource][dropFolderFileId]=%7B%7D&resource[resource][entryId]=%7B%7D&resource[resource][fileSyncObjectType]=%7B%7D&resource[resource][flavorParamsId]=%7B%7D&resource[resource][forceAsyncDownload]=%7B%7D&resource[resource][keepOriginalFile]=%7B%7D&resource[resource][keyPassphrase]=%7B%7D&resource[resource][localFilePath]=%7B%7D&resource[resource][objectId]=%7B%7D&resource[resource][objectSubType]=%7B%7D&resource[resource][objectType]=%7B%7D&resource[resource][privateKey]=%7B%7D&resource[resource][publicKey]=%7B%7D&resource[resource][resources]=%7B%7D&resource[resource][resource][assetId]=%7B%7D&resource[resource][resource][content]=%7B%7D&resource[resource][resource][dropFolderFileId]=%7B%7D&resource[resource][resource][entryId]=%7B%7D&resource[resource][resource][fileSyncObjectType]=%7B%7D&resource[resource][resource][flavorParamsId]=%7B%7D&resource[resource][resource][forceAsyncDownload]=%7B%7D&resource[resource][resource][keepOriginalFile]=%7B%7D&resource[resource][resource][keyPassphrase]=%7B%7D&resource[resource][resource][localFilePath]=%7B%7D&resource[resource][resource][objectId]=%7B%7D&resource[resource][resource][objectSubType]=%7B%7D&resource[resource][resource][objectType]=%7B%7D&resource[resource][resource][privateKey]=%7B%7D&resource[resource][resource][publicKey]=%7B%7D&resource[resource][resource][resources]=%7B%7D&resource[resource][resource][resource][assetId]=%7B%7D&resource[resource][resource][resource][content]=%7B%7D&resource[resource][resource][resource][dropFolderFileId]=%7B%7D&resource[resource][resource][resource][entryId]=%7B%7D&resource[resource][resource][resource][fileSyncObjectType]=%7B%7D&resource[resource][resource][resource][flavorParamsId]=%7B%7D&resource[resource][resource][resource][forceAsyncDownload]=%7B%7D&resource[resource][resource][resource][keepOriginalFile]=%7B%7D&resource[resource][resource][resource][keyPassphrase]=%7B%7D&resource[resource][resource][resource][localFilePath]=%7B%7D&resource[resource][resource][resource][objectId]=%7B%7D&resource[resource][resource][resource][objectSubType]=%7B%7D&resource[resource][resource][resource][objectType]=%7B%7D&resource[resource][resource][resource][privateKey]=%7B%7D&resource[resource][resource][resource][publicKey]=%7B%7D&resource[resource][resource][resource][resources]=%7B%7D&resource[resource][resource][resource][storageProfileId]=%7B%7D&resource[resource][resource][resource][token]=%7B%7D&resource[resource][resource][resource][url]=%7B%7D&resource[resource][resource][resource][version]=%7B%7D&resource[resource][resource][storageProfileId]=%7B%7D&resource[resource][resource][token]=%7B%7D&resource[resource][resource][url]=%7B%7D&resource[resource][resource][version]=%7B%7D&resource[resource][storageProfileId]=%7B%7D&resource[resource][token]=%7B%7D&resource[resource][url]=%7B%7D&resource[resource][version]=%7B%7D&resource[storageProfileId]=%7B%7D&resource[token]=%7B%7D&resource[url]=%7B%7D&resource[version]=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "resource[fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "resource[resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "resource[resource][resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "resource[resource][resource][resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                }
              ]
            },
            "description": "Attach content resource to entry in status NO_MEDIA"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "de6ea35c-4436-4064-a0fc-fd78e4c20b17"
            }
          ]
        },
        {
          "id": "df11a132-8aad-411c-ab46-126fe2233b93",
          "name": "baseEntry.updateContent",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/baseentry/action/updateContent?advancedOptions[keepManualThumbnails]=%7B%7D&advancedOptions[pluginOptionItems]=%7B%7D&conversionProfileId=%7B%7D&entryId=%7B%7D&No Name=%7B%7D&resource[assetId]=%7B%7D&resource[content]=%7B%7D&resource[dropFolderFileId]=%7B%7D&resource[entryId]=%7B%7D&resource[fileSyncObjectType]=%7B%7D&resource[flavorParamsId]=%7B%7D&resource[forceAsyncDownload]=%7B%7D&resource[keepOriginalFile]=%7B%7D&resource[keyPassphrase]=%7B%7D&resource[localFilePath]=%7B%7D&resource[objectId]=%7B%7D&resource[objectSubType]=%7B%7D&resource[objectType]=%7B%7D&resource[privateKey]=%7B%7D&resource[publicKey]=%7B%7D&resource[resources]=%7B%7D&resource[resource][assetId]=%7B%7D&resource[resource][content]=%7B%7D&resource[resource][dropFolderFileId]=%7B%7D&resource[resource][entryId]=%7B%7D&resource[resource][fileSyncObjectType]=%7B%7D&resource[resource][flavorParamsId]=%7B%7D&resource[resource][forceAsyncDownload]=%7B%7D&resource[resource][keepOriginalFile]=%7B%7D&resource[resource][keyPassphrase]=%7B%7D&resource[resource][localFilePath]=%7B%7D&resource[resource][objectId]=%7B%7D&resource[resource][objectSubType]=%7B%7D&resource[resource][objectType]=%7B%7D&resource[resource][privateKey]=%7B%7D&resource[resource][publicKey]=%7B%7D&resource[resource][resources]=%7B%7D&resource[resource][resource][assetId]=%7B%7D&resource[resource][resource][content]=%7B%7D&resource[resource][resource][dropFolderFileId]=%7B%7D&resource[resource][resource][entryId]=%7B%7D&resource[resource][resource][fileSyncObjectType]=%7B%7D&resource[resource][resource][flavorParamsId]=%7B%7D&resource[resource][resource][forceAsyncDownload]=%7B%7D&resource[resource][resource][keepOriginalFile]=%7B%7D&resource[resource][resource][keyPassphrase]=%7B%7D&resource[resource][resource][localFilePath]=%7B%7D&resource[resource][resource][objectId]=%7B%7D&resource[resource][resource][objectSubType]=%7B%7D&resource[resource][resource][objectType]=%7B%7D&resource[resource][resource][privateKey]=%7B%7D&resource[resource][resource][publicKey]=%7B%7D&resource[resource][resource][resources]=%7B%7D&resource[resource][resource][resource][assetId]=%7B%7D&resource[resource][resource][resource][content]=%7B%7D&resource[resource][resource][resource][dropFolderFileId]=%7B%7D&resource[resource][resource][resource][entryId]=%7B%7D&resource[resource][resource][resource][fileSyncObjectType]=%7B%7D&resource[resource][resource][resource][flavorParamsId]=%7B%7D&resource[resource][resource][resource][forceAsyncDownload]=%7B%7D&resource[resource][resource][resource][keepOriginalFile]=%7B%7D&resource[resource][resource][resource][keyPassphrase]=%7B%7D&resource[resource][resource][resource][localFilePath]=%7B%7D&resource[resource][resource][resource][objectId]=%7B%7D&resource[resource][resource][resource][objectSubType]=%7B%7D&resource[resource][resource][resource][objectType]=%7B%7D&resource[resource][resource][resource][privateKey]=%7B%7D&resource[resource][resource][resource][publicKey]=%7B%7D&resource[resource][resource][resource][resources]=%7B%7D&resource[resource][resource][resource][storageProfileId]=%7B%7D&resource[resource][resource][resource][token]=%7B%7D&resource[resource][resource][resource][url]=%7B%7D&resource[resource][resource][resource][version]=%7B%7D&resource[resource][resource][storageProfileId]=%7B%7D&resource[resource][resource][token]=%7B%7D&resource[resource][resource][url]=%7B%7D&resource[resource][resource][version]=%7B%7D&resource[resource][storageProfileId]=%7B%7D&resource[resource][token]=%7B%7D&resource[resource][url]=%7B%7D&resource[resource][version]=%7B%7D&resource[storageProfileId]=%7B%7D&resource[token]=%7B%7D&resource[url]=%7B%7D&resource[version]=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "resource[fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "resource[resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "resource[resource][resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "resource[resource][resource][resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                }
              ]
            },
            "description": "Update the content resource associated with the entry."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5fe2fb1a-800a-40ec-a3b5-c5da4f3985d3"
            }
          ]
        },
        {
          "id": "f590d5fc-2bb3-4f5e-be64-771f4ed2b9f2",
          "name": "captionAsset.setContent",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/caption_captionasset/action/setContent?contentResource[assetId]=%7B%7D&contentResource[content]=%7B%7D&contentResource[dropFolderFileId]=%7B%7D&contentResource[entryId]=%7B%7D&contentResource[fileSyncObjectType]=%7B%7D&contentResource[flavorParamsId]=%7B%7D&contentResource[forceAsyncDownload]=%7B%7D&contentResource[keepOriginalFile]=%7B%7D&contentResource[keyPassphrase]=%7B%7D&contentResource[localFilePath]=%7B%7D&contentResource[objectId]=%7B%7D&contentResource[objectSubType]=%7B%7D&contentResource[objectType]=%7B%7D&contentResource[privateKey]=%7B%7D&contentResource[publicKey]=%7B%7D&contentResource[resources]=%7B%7D&contentResource[resource][assetId]=%7B%7D&contentResource[resource][content]=%7B%7D&contentResource[resource][dropFolderFileId]=%7B%7D&contentResource[resource][entryId]=%7B%7D&contentResource[resource][fileSyncObjectType]=%7B%7D&contentResource[resource][flavorParamsId]=%7B%7D&contentResource[resource][forceAsyncDownload]=%7B%7D&contentResource[resource][keepOriginalFile]=%7B%7D&contentResource[resource][keyPassphrase]=%7B%7D&contentResource[resource][localFilePath]=%7B%7D&contentResource[resource][objectId]=%7B%7D&contentResource[resource][objectSubType]=%7B%7D&contentResource[resource][objectType]=%7B%7D&contentResource[resource][privateKey]=%7B%7D&contentResource[resource][publicKey]=%7B%7D&contentResource[resource][resources]=%7B%7D&contentResource[resource][resource][assetId]=%7B%7D&contentResource[resource][resource][content]=%7B%7D&contentResource[resource][resource][dropFolderFileId]=%7B%7D&contentResource[resource][resource][entryId]=%7B%7D&contentResource[resource][resource][fileSyncObjectType]=%7B%7D&contentResource[resource][resource][flavorParamsId]=%7B%7D&contentResource[resource][resource][forceAsyncDownload]=%7B%7D&contentResource[resource][resource][keepOriginalFile]=%7B%7D&contentResource[resource][resource][keyPassphrase]=%7B%7D&contentResource[resource][resource][localFilePath]=%7B%7D&contentResource[resource][resource][objectId]=%7B%7D&contentResource[resource][resource][objectSubType]=%7B%7D&contentResource[resource][resource][objectType]=%7B%7D&contentResource[resource][resource][privateKey]=%7B%7D&contentResource[resource][resource][publicKey]=%7B%7D&contentResource[resource][resource][resources]=%7B%7D&contentResource[resource][resource][resource][assetId]=%7B%7D&contentResource[resource][resource][resource][content]=%7B%7D&contentResource[resource][resource][resource][dropFolderFileId]=%7B%7D&contentResource[resource][resource][resource][entryId]=%7B%7D&contentResource[resource][resource][resource][fileSyncObjectType]=%7B%7D&contentResource[resource][resource][resource][flavorParamsId]=%7B%7D&contentResource[resource][resource][resource][forceAsyncDownload]=%7B%7D&contentResource[resource][resource][resource][keepOriginalFile]=%7B%7D&contentResource[resource][resource][resource][keyPassphrase]=%7B%7D&contentResource[resource][resource][resource][localFilePath]=%7B%7D&contentResource[resource][resource][resource][objectId]=%7B%7D&contentResource[resource][resource][resource][objectSubType]=%7B%7D&contentResource[resource][resource][resource][objectType]=%7B%7D&contentResource[resource][resource][resource][privateKey]=%7B%7D&contentResource[resource][resource][resource][publicKey]=%7B%7D&contentResource[resource][resource][resource][resources]=%7B%7D&contentResource[resource][resource][resource][storageProfileId]=%7B%7D&contentResource[resource][resource][resource][token]=%7B%7D&contentResource[resource][resource][resource][url]=%7B%7D&contentResource[resource][resource][resource][version]=%7B%7D&contentResource[resource][resource][storageProfileId]=%7B%7D&contentResource[resource][resource][token]=%7B%7D&contentResource[resource][resource][url]=%7B%7D&contentResource[resource][resource][version]=%7B%7D&contentResource[resource][storageProfileId]=%7B%7D&contentResource[resource][token]=%7B%7D&contentResource[resource][url]=%7B%7D&contentResource[resource][version]=%7B%7D&contentResource[storageProfileId]=%7B%7D&contentResource[token]=%7B%7D&contentResource[url]=%7B%7D&contentResource[version]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "contentResource[fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "contentResource[resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "contentResource[resource][resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "contentResource[resource][resource][resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                }
              ]
            },
            "description": "Update content of caption asset"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5ba90414-a207-4f61-aca7-1a10a56866db"
            }
          ]
        },
        {
          "id": "6e4a26cb-a6f7-432a-a04f-5a87ffc2e208",
          "name": "contentDistributionBatch.createRequiredJobs",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_contentdistributionbatch/action/createRequiredJobs?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "creates all required jobs according to entry distribution dirty flags"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dd38c63d-9adc-47bf-ae6b-e1700fc7a2ae"
            }
          ]
        },
        {
          "id": "a5768916-aa49-4d60-8bc5-80fc0138bf63",
          "name": "contentDistributionBatch.getAssetUrl",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_contentdistributionbatch/action/getAssetUrl?assetId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "returns absolute valid url for asset file"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e9ce0ad-179a-47ca-b80f-f98c0f5775dc"
            }
          ]
        },
        {
          "id": "111db7ca-9cda-498e-b61d-7716e61df575",
          "name": "contentDistributionBatch.updateSunStatus",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_contentdistributionbatch/action/updateSunStatus?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "updates entry distribution sun status in the search engine"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "22583a79-21b3-43b9-be70-84490d5f310e"
            }
          ]
        },
        {
          "id": "6e078bac-0817-480c-b7f4-b80bb2256ea5",
          "name": "distributionProfile.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_distributionprofile/action/add?distributionProfile[accountId]=%7B%7D&distributionProfile[adFreeApplicationGuid]=%7B%7D&distributionProfile[adServerPartnerId]=%7B%7D&distributionProfile[allowAdsenseForVideo]=%7B%7D&distributionProfile[allowComments]=%7B%7D&distributionProfile[allowDownload]=%7B%7D&distributionProfile[allowEmbedding]=%7B%7D&distributionProfile[allowInvideo]=%7B%7D&distributionProfile[allowMidRollAds]=%7B%7D&distributionProfile[allowPostRollAds]=%7B%7D&distributionProfile[allowPreRollAds]=%7B%7D&distributionProfile[allowRatings]=%7B%7D&distributionProfile[allowResponses]=%7B%7D&distributionProfile[allowStreaming]=%7B%7D&distributionProfile[allowSyndication]=%7B%7D&distributionProfile[apiAuthorizeUrl]=%7B%7D&distributionProfile[apiHostUrl]=%7B%7D&distributionProfile[apikey]=%7B%7D&distributionProfile[asperaHost]=%7B%7D&distributionProfile[asperaLogin]=%7B%7D&distributionProfile[asperaPass]=%7B%7D&distributionProfile[asperaPrivateKey]=%7B%7D&distributionProfile[asperaPublicKey]=%7B%7D&distributionProfile[assetFilenameXslt]=%7B%7D&distributionProfile[assumeSuccess]=%7B%7D&distributionProfile[autoCreateFlavors]=%7B%7D&distributionProfile[autoCreateThumb]=%7B%7D&distributionProfile[backgroundImageStandard]=%7B%7D&distributionProfile[backgroundImageWide]=%7B%7D&distributionProfile[basePath]=%7B%7D&distributionProfile[blockOutsideOwnership]=%7B%7D&distributionProfile[bodyXslt]=%7B%7D&distributionProfile[captionAutosync]=%7B%7D&distributionProfile[categoryId]=%7B%7D&distributionProfile[certificateKey]=%7B%7D&distributionProfile[channelCopyright]=%7B%7D&distributionProfile[channelDescription]=%7B%7D&distributionProfile[channelGenerator]=%7B%7D&distributionProfile[channelGuid]=%7B%7D&distributionProfile[channelImageHeight]=%7B%7D&distributionProfile[channelImageLink]=%7B%7D&distributionProfile[channelImageTitle]=%7B%7D&distributionProfile[channelImageUrl]=%7B%7D&distributionProfile[channelImageWidth]=%7B%7D&distributionProfile[channelLanguage]=%7B%7D&distributionProfile[channelLink]=%7B%7D&distributionProfile[channelManagingEditor]=%7B%7D&distributionProfile[channelRating]=%7B%7D&distributionProfile[channelTitle]=%7B%7D&distributionProfile[claimType]=%7B%7D&distributionProfile[commercialPolicy]=%7B%7D&distributionProfile[contactEmail]=%7B%7D&distributionProfile[contactTelephone]=%7B%7D&distributionProfile[contentOwner]=%7B%7D&distributionProfile[copyright]=%7B%7D&distributionProfile[cPlatformTvSeriesField]=%7B%7D&distributionProfile[cPlatformTvSeries]=%7B%7D&distributionProfile[csId]=%7B%7D&distributionProfile[cuePointsProvider]=%7B%7D&distributionProfile[defaultCategory]=%7B%7D&distributionProfile[deleteEnabled]=%7B%7D&distributionProfile[deleteReference]=%7B%7D&distributionProfile[disableEpisodeNumberCustomValidation]=%7B%7D&distributionProfile[disableMetadata]=%7B%7D&distributionProfile[distributeCaptions]=%7B%7D&distributionProfile[distributeCuePoints]=%7B%7D&distributionProfile[distributeRemoteCaptionAssetContent]=%7B%7D&distributionProfile[distributeRemoteFlavorAssetContent]=%7B%7D&distributionProfile[distributeRemoteThumbAssetContent]=%7B%7D&distributionProfile[domainGuid]=%7B%7D&distributionProfile[domainName]=%7B%7D&distributionProfile[domain]=%7B%7D&distributionProfile[downloadPriceCode]=%7B%7D&distributionProfile[email]=%7B%7D&distributionProfile[enableAdServer]=%7B%7D&distributionProfile[entitlements]=%7B%7D&distributionProfile[entitlement]=%7B%7D&distributionProfile[feedAuthorName]=%7B%7D&distributionProfile[feedCopyright]=%7B%7D&distributionProfile[feedDescription]=%7B%7D&distributionProfile[feedImageHeight]=%7B%7D&distributionProfile[feedImageLink]=%7B%7D&distributionProfile[feedImageTitle]=%7B%7D&distributionProfile[feedImageUrl]=%7B%7D&distributionProfile[feedImageWidth]=%7B%7D&distributionProfile[feedLanguage]=%7B%7D&distributionProfile[feedLastBuildDate]=%7B%7D&distributionProfile[feedLink]=%7B%7D&distributionProfile[feedSpecVersion]=%7B%7D&distributionProfile[feedSubtitle]=%7B%7D&distributionProfile[feedTitle]=%7B%7D&distributionProfile[fieldConfigArray]=%7B%7D&distributionProfile[flavorAssetFilenameXslt]=%7B%7D&distributionProfile[flvFlavorParamsId]=%7B%7D&distributionProfile[ftpHost]=%7B%7D&distributionProfile[ftpLogin]=%7B%7D&distributionProfile[ftpPassword]=%7B%7D&distributionProfile[ftpPass]=%7B%7D&distributionProfile[ftpPath]=%7B%7D&distributionProfile[ftpUsername]=%7B%7D&distributionProfile[genericProviderId]=%7B%7D&distributionProfile[geoBlockingMapping]=%7B%7D&distributionProfile[googleClientId]=%7B%7D&distributionProfile[googleClientSecret]=%7B%7D&distributionProfile[googleTokenData]=%7B%7D&distributionProfile[hideViewCount]=%7B%7D&distributionProfile[host]=%7B%7D&distributionProfile[ignoreSchedulingInFeed]=%7B%7D&distributionProfile[ingestUrl]=%7B%7D&distributionProfile[instreamStandard]=%7B%7D&distributionProfile[instreamTrueview]=%7B%7D&distributionProfile[ips]=%7B%7D&distributionProfile[itemLink]=%7B%7D&distributionProfile[itemMediaRating]=%7B%7D&distributionProfile[itemsPerPage]=%7B%7D&distributionProfile[itemType]=%7B%7D&distributionProfile[itemXpathsToExtend]=%7B%7D&distributionProfile[mapAccessControlProfileIds]=%7B%7D&distributionProfile[mapCaptionParamsIds]=%7B%7D&distributionProfile[mapConversionProfileIds]=%7B%7D&distributionProfile[mapFlavorParamsIds]=%7B%7D&distributionProfile[mapMetadataProfileIds]=%7B%7D&distributionProfile[mapStorageProfileIds]=%7B%7D&distributionProfile[mapThumbParamsIds]=%7B%7D&distributionProfile[metadataFilenameXslt]=%7B%7D&distributionProfile[metadataProfileId]=%7B%7D&distributionProfile[metadataXpathsTriggerUpdate]=%7B%7D&distributionProfile[metadataXslt]=%7B%7D&distributionProfile[msnvideoCat]=%7B%7D&distributionProfile[msnvideoTopCat]=%7B%7D&distributionProfile[msnvideoTop]=%7B%7D&distributionProfile[name]=%7B%7D&distributionProfile[notificationEmail]=%7B%7D&distributionProfile[objectType]=%7B%7D&distributionProfile[optionalAssetDistributionRules]=%7B%7D&distributionProfile[optionalFlavorParamsIds]=%7B%7D&distributionProfile[optionalThumbDimensions]=%7B%7D&distributionProfile[overrideManualEdits]=%7B%7D&distributionProfile[ownerName]=%7B%7D&distributionProfile[pageAccessToken]=%7B%7D&distributionProfile[pageGroup]=%7B%7D&distributionProfile[pageId]=%7B%7D&distributionProfile[passphrase]=%7B%7D&distributionProfile[password]=%7B%7D&distributionProfile[permissions]=%7B%7D&distributionProfile[port]=%7B%7D&distributionProfile[priority]=%7B%7D&distributionProfile[privacyStatus]=%7B%7D&distributionProfile[processFeed]=%7B%7D&distributionProfile[protocol]=%7B%7D&distributionProfile[providerId]=%7B%7D&distributionProfile[providerName]=%7B%7D&distributionProfile[providerType]=%7B%7D&distributionProfile[rating]=%7B%7D&distributionProfile[recommendedDcForDownload]=%7B%7D&distributionProfile[recommendedDcForExecute]=%7B%7D&distributionProfile[recommendedStorageProfileForDownload]=%7B%7D&distributionProfile[releaseClaims]=%7B%7D&distributionProfile[remoteAssetParamsId]=%7B%7D&distributionProfile[replaceAirDates]=%7B%7D&distributionProfile[replaceGroup]=%7B%7D&distributionProfile[reportEnabled]=%7B%7D&distributionProfile[requiredAssetDistributionRules]=%7B%7D&distributionProfile[requiredFlavorParamsIds]=%7B%7D&distributionProfile[requiredThumbDimensions]=%7B%7D&distributionProfile[reRequestPermissions]=%7B%7D&distributionProfile[seasonNumber]=%7B%7D&distributionProfile[seasonSynopsis]=%7B%7D&distributionProfile[seasonTuneInInformation]=%7B%7D&distributionProfile[sendMetadataAfterAssets]=%7B%7D&distributionProfile[seriesAdditionalCategories]=%7B%7D&distributionProfile[seriesChannel]=%7B%7D&distributionProfile[seriesPrimaryCategory]=%7B%7D&distributionProfile[sftpBaseDir]=%7B%7D&distributionProfile[sftpBasePath]=%7B%7D&distributionProfile[sftpHost]=%7B%7D&distributionProfile[sftpLogin]=%7B%7D&distributionProfile[sftpPass]=%7B%7D&distributionProfile[sftpPort]=%7B%7D&distributionProfile[sftpPrivateKey]=%7B%7D&distributionProfile[sftpPublicKey]=%7B%7D&distributionProfile[shouldAddThumbExtension]=%7B%7D&distributionProfile[shouldIncludeCaptions]=%7B%7D&distributionProfile[shouldIncludeCuePoints]=%7B%7D&distributionProfile[slFlavorParamsId]=%7B%7D&distributionProfile[slHdFlavorParamsId]=%7B%7D&distributionProfile[sourceFlavorParamsId]=%7B%7D&distributionProfile[sourceFriendlyName]=%7B%7D&distributionProfile[source]=%7B%7D&distributionProfile[state]=%7B%7D&distributionProfile[status]=%7B%7D&distributionProfile[storageProfileId]=%7B%7D&distributionProfile[streamingPriceCode]=%7B%7D&distributionProfile[strict]=%7B%7D&distributionProfile[submitAction][ftpPassiveMode]=%7B%7D&distributionProfile[submitAction][httpFieldName]=%7B%7D&distributionProfile[submitAction][httpFileName]=%7B%7D&distributionProfile[submitAction][password]=%7B%7D&distributionProfile[submitAction][protocol]=%7B%7D&distributionProfile[submitAction][serverPath]=%7B%7D&distributionProfile[submitAction][serverUrl]=%7B%7D&distributionProfile[submitAction][username]=%7B%7D&distributionProfile[submitEnabled]=%7B%7D&distributionProfile[sunriseDefaultOffset]=%7B%7D&distributionProfile[sunsetDefaultOffset]=%7B%7D&distributionProfile[tags]=%7B%7D&distributionProfile[targetAccountId]=%7B%7D&distributionProfile[targetLoginId]=%7B%7D&distributionProfile[targetLoginPassword]=%7B%7D&distributionProfile[targetServiceUrl]=%7B%7D&distributionProfile[target]=%7B%7D&distributionProfile[thumbnailAssetFilenameXslt]=%7B%7D&distributionProfile[ugcPolicy]=%7B%7D&distributionProfile[updateEnabled]=%7B%7D&distributionProfile[upstreamNetworkId]=%7B%7D&distributionProfile[upstreamNetworkName]=%7B%7D&distributionProfile[upstreamVideoId]=%7B%7D&distributionProfile[urgentReference]=%7B%7D&distributionProfile[useCategoryEntries]=%7B%7D&distributionProfile[userAccessToken]=%7B%7D&distributionProfile[username]=%7B%7D&distributionProfile[user]=%7B%7D&distributionProfile[videoMediaType]=%7B%7D&distributionProfile[wmvFlavorParamsId]=%7B%7D&distributionProfile[xsltFile]=%7B%7D&distributionProfile[xsl]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add new Distribution Profile"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5b698cbe-ee67-4b28-b7fb-3f07d807692e"
            }
          ]
        },
        {
          "id": "ff717230-7c2d-48d1-ad23-a9009ac42229",
          "name": "distributionProfile.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_distributionprofile/action/delete?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete Distribution Profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8560c81f-d02d-4371-8610-75b67805b0ae"
            }
          ]
        },
        {
          "id": "2a9f5038-275e-492c-922d-f12f2484efd9",
          "name": "distributionProfile.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_distributionprofile/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Distribution Profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a1d82be1-2397-45c8-aa7e-709ec75d8f1e"
            }
          ]
        },
        {
          "id": "327bc769-65bb-446d-b658-65229cae9b3c",
          "name": "distributionProfile.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_distributionprofile/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List all distribution providers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "78914338-d0f4-4c68-9583-bf308176c9f3"
            }
          ]
        },
        {
          "id": "472777f9-8021-4c4c-9ab7-e67e9b26f16e",
          "name": "distributionProfile.listByPartner",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_distributionprofile/action/listByPartner?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[groupTypeEq]=%7B%7D&filter[groupTypeIn]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[idNotIn]=%7B%7D&filter[nameEqual]=%7B%7D&filter[nameLike]=%7B%7D&filter[nameMultiLikeAnd]=%7B%7D&filter[nameMultiLikeOr]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[partnerGroupTypeEqual]=%7B%7D&filter[partnerNameDescriptionWebsiteAdminNameAdminEmailLike]=%7B%7D&filter[partnerPackageEqual]=%7B%7D&filter[partnerPackageGreaterThanOrEqual]=%7B%7D&filter[partnerPackageIn]=%7B%7D&filter[partnerPackageLessThanOrEqual]=%7B%7D&filter[partnerPermissionsExist]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Service Contentdistribution Distributionprofile Action Listbypartner"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3f0d467d-bac9-4b26-a227-a26dbdc0ddca"
            }
          ]
        },
        {
          "id": "c2971704-85f1-434b-9a88-65d5356b647d",
          "name": "distributionProfile.update",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_distributionprofile/action/update?distributionProfile[accountId]=%7B%7D&distributionProfile[adFreeApplicationGuid]=%7B%7D&distributionProfile[adServerPartnerId]=%7B%7D&distributionProfile[allowAdsenseForVideo]=%7B%7D&distributionProfile[allowComments]=%7B%7D&distributionProfile[allowDownload]=%7B%7D&distributionProfile[allowEmbedding]=%7B%7D&distributionProfile[allowInvideo]=%7B%7D&distributionProfile[allowMidRollAds]=%7B%7D&distributionProfile[allowPostRollAds]=%7B%7D&distributionProfile[allowPreRollAds]=%7B%7D&distributionProfile[allowRatings]=%7B%7D&distributionProfile[allowResponses]=%7B%7D&distributionProfile[allowStreaming]=%7B%7D&distributionProfile[allowSyndication]=%7B%7D&distributionProfile[apiAuthorizeUrl]=%7B%7D&distributionProfile[apiHostUrl]=%7B%7D&distributionProfile[apikey]=%7B%7D&distributionProfile[asperaHost]=%7B%7D&distributionProfile[asperaLogin]=%7B%7D&distributionProfile[asperaPass]=%7B%7D&distributionProfile[asperaPrivateKey]=%7B%7D&distributionProfile[asperaPublicKey]=%7B%7D&distributionProfile[assetFilenameXslt]=%7B%7D&distributionProfile[assumeSuccess]=%7B%7D&distributionProfile[autoCreateFlavors]=%7B%7D&distributionProfile[autoCreateThumb]=%7B%7D&distributionProfile[backgroundImageStandard]=%7B%7D&distributionProfile[backgroundImageWide]=%7B%7D&distributionProfile[basePath]=%7B%7D&distributionProfile[blockOutsideOwnership]=%7B%7D&distributionProfile[bodyXslt]=%7B%7D&distributionProfile[captionAutosync]=%7B%7D&distributionProfile[categoryId]=%7B%7D&distributionProfile[certificateKey]=%7B%7D&distributionProfile[channelCopyright]=%7B%7D&distributionProfile[channelDescription]=%7B%7D&distributionProfile[channelGenerator]=%7B%7D&distributionProfile[channelGuid]=%7B%7D&distributionProfile[channelImageHeight]=%7B%7D&distributionProfile[channelImageLink]=%7B%7D&distributionProfile[channelImageTitle]=%7B%7D&distributionProfile[channelImageUrl]=%7B%7D&distributionProfile[channelImageWidth]=%7B%7D&distributionProfile[channelLanguage]=%7B%7D&distributionProfile[channelLink]=%7B%7D&distributionProfile[channelManagingEditor]=%7B%7D&distributionProfile[channelRating]=%7B%7D&distributionProfile[channelTitle]=%7B%7D&distributionProfile[claimType]=%7B%7D&distributionProfile[commercialPolicy]=%7B%7D&distributionProfile[contactEmail]=%7B%7D&distributionProfile[contactTelephone]=%7B%7D&distributionProfile[contentOwner]=%7B%7D&distributionProfile[copyright]=%7B%7D&distributionProfile[cPlatformTvSeriesField]=%7B%7D&distributionProfile[cPlatformTvSeries]=%7B%7D&distributionProfile[csId]=%7B%7D&distributionProfile[cuePointsProvider]=%7B%7D&distributionProfile[defaultCategory]=%7B%7D&distributionProfile[deleteEnabled]=%7B%7D&distributionProfile[deleteReference]=%7B%7D&distributionProfile[disableEpisodeNumberCustomValidation]=%7B%7D&distributionProfile[disableMetadata]=%7B%7D&distributionProfile[distributeCaptions]=%7B%7D&distributionProfile[distributeCuePoints]=%7B%7D&distributionProfile[distributeRemoteCaptionAssetContent]=%7B%7D&distributionProfile[distributeRemoteFlavorAssetContent]=%7B%7D&distributionProfile[distributeRemoteThumbAssetContent]=%7B%7D&distributionProfile[domainGuid]=%7B%7D&distributionProfile[domainName]=%7B%7D&distributionProfile[domain]=%7B%7D&distributionProfile[downloadPriceCode]=%7B%7D&distributionProfile[email]=%7B%7D&distributionProfile[enableAdServer]=%7B%7D&distributionProfile[entitlements]=%7B%7D&distributionProfile[entitlement]=%7B%7D&distributionProfile[feedAuthorName]=%7B%7D&distributionProfile[feedCopyright]=%7B%7D&distributionProfile[feedDescription]=%7B%7D&distributionProfile[feedImageHeight]=%7B%7D&distributionProfile[feedImageLink]=%7B%7D&distributionProfile[feedImageTitle]=%7B%7D&distributionProfile[feedImageUrl]=%7B%7D&distributionProfile[feedImageWidth]=%7B%7D&distributionProfile[feedLanguage]=%7B%7D&distributionProfile[feedLastBuildDate]=%7B%7D&distributionProfile[feedLink]=%7B%7D&distributionProfile[feedSpecVersion]=%7B%7D&distributionProfile[feedSubtitle]=%7B%7D&distributionProfile[feedTitle]=%7B%7D&distributionProfile[fieldConfigArray]=%7B%7D&distributionProfile[flavorAssetFilenameXslt]=%7B%7D&distributionProfile[flvFlavorParamsId]=%7B%7D&distributionProfile[ftpHost]=%7B%7D&distributionProfile[ftpLogin]=%7B%7D&distributionProfile[ftpPassword]=%7B%7D&distributionProfile[ftpPass]=%7B%7D&distributionProfile[ftpPath]=%7B%7D&distributionProfile[ftpUsername]=%7B%7D&distributionProfile[genericProviderId]=%7B%7D&distributionProfile[geoBlockingMapping]=%7B%7D&distributionProfile[googleClientId]=%7B%7D&distributionProfile[googleClientSecret]=%7B%7D&distributionProfile[googleTokenData]=%7B%7D&distributionProfile[hideViewCount]=%7B%7D&distributionProfile[host]=%7B%7D&distributionProfile[ignoreSchedulingInFeed]=%7B%7D&distributionProfile[ingestUrl]=%7B%7D&distributionProfile[instreamStandard]=%7B%7D&distributionProfile[instreamTrueview]=%7B%7D&distributionProfile[ips]=%7B%7D&distributionProfile[itemLink]=%7B%7D&distributionProfile[itemMediaRating]=%7B%7D&distributionProfile[itemsPerPage]=%7B%7D&distributionProfile[itemType]=%7B%7D&distributionProfile[itemXpathsToExtend]=%7B%7D&distributionProfile[mapAccessControlProfileIds]=%7B%7D&distributionProfile[mapCaptionParamsIds]=%7B%7D&distributionProfile[mapConversionProfileIds]=%7B%7D&distributionProfile[mapFlavorParamsIds]=%7B%7D&distributionProfile[mapMetadataProfileIds]=%7B%7D&distributionProfile[mapStorageProfileIds]=%7B%7D&distributionProfile[mapThumbParamsIds]=%7B%7D&distributionProfile[metadataFilenameXslt]=%7B%7D&distributionProfile[metadataProfileId]=%7B%7D&distributionProfile[metadataXpathsTriggerUpdate]=%7B%7D&distributionProfile[metadataXslt]=%7B%7D&distributionProfile[msnvideoCat]=%7B%7D&distributionProfile[msnvideoTopCat]=%7B%7D&distributionProfile[msnvideoTop]=%7B%7D&distributionProfile[name]=%7B%7D&distributionProfile[notificationEmail]=%7B%7D&distributionProfile[objectType]=%7B%7D&distributionProfile[optionalAssetDistributionRules]=%7B%7D&distributionProfile[optionalFlavorParamsIds]=%7B%7D&distributionProfile[optionalThumbDimensions]=%7B%7D&distributionProfile[overrideManualEdits]=%7B%7D&distributionProfile[ownerName]=%7B%7D&distributionProfile[pageAccessToken]=%7B%7D&distributionProfile[pageGroup]=%7B%7D&distributionProfile[pageId]=%7B%7D&distributionProfile[passphrase]=%7B%7D&distributionProfile[password]=%7B%7D&distributionProfile[permissions]=%7B%7D&distributionProfile[port]=%7B%7D&distributionProfile[priority]=%7B%7D&distributionProfile[privacyStatus]=%7B%7D&distributionProfile[processFeed]=%7B%7D&distributionProfile[protocol]=%7B%7D&distributionProfile[providerId]=%7B%7D&distributionProfile[providerName]=%7B%7D&distributionProfile[providerType]=%7B%7D&distributionProfile[rating]=%7B%7D&distributionProfile[recommendedDcForDownload]=%7B%7D&distributionProfile[recommendedDcForExecute]=%7B%7D&distributionProfile[recommendedStorageProfileForDownload]=%7B%7D&distributionProfile[releaseClaims]=%7B%7D&distributionProfile[remoteAssetParamsId]=%7B%7D&distributionProfile[replaceAirDates]=%7B%7D&distributionProfile[replaceGroup]=%7B%7D&distributionProfile[reportEnabled]=%7B%7D&distributionProfile[requiredAssetDistributionRules]=%7B%7D&distributionProfile[requiredFlavorParamsIds]=%7B%7D&distributionProfile[requiredThumbDimensions]=%7B%7D&distributionProfile[reRequestPermissions]=%7B%7D&distributionProfile[seasonNumber]=%7B%7D&distributionProfile[seasonSynopsis]=%7B%7D&distributionProfile[seasonTuneInInformation]=%7B%7D&distributionProfile[sendMetadataAfterAssets]=%7B%7D&distributionProfile[seriesAdditionalCategories]=%7B%7D&distributionProfile[seriesChannel]=%7B%7D&distributionProfile[seriesPrimaryCategory]=%7B%7D&distributionProfile[sftpBaseDir]=%7B%7D&distributionProfile[sftpBasePath]=%7B%7D&distributionProfile[sftpHost]=%7B%7D&distributionProfile[sftpLogin]=%7B%7D&distributionProfile[sftpPass]=%7B%7D&distributionProfile[sftpPort]=%7B%7D&distributionProfile[sftpPrivateKey]=%7B%7D&distributionProfile[sftpPublicKey]=%7B%7D&distributionProfile[shouldAddThumbExtension]=%7B%7D&distributionProfile[shouldIncludeCaptions]=%7B%7D&distributionProfile[shouldIncludeCuePoints]=%7B%7D&distributionProfile[slFlavorParamsId]=%7B%7D&distributionProfile[slHdFlavorParamsId]=%7B%7D&distributionProfile[sourceFlavorParamsId]=%7B%7D&distributionProfile[sourceFriendlyName]=%7B%7D&distributionProfile[source]=%7B%7D&distributionProfile[state]=%7B%7D&distributionProfile[status]=%7B%7D&distributionProfile[storageProfileId]=%7B%7D&distributionProfile[streamingPriceCode]=%7B%7D&distributionProfile[strict]=%7B%7D&distributionProfile[submitAction][ftpPassiveMode]=%7B%7D&distributionProfile[submitAction][httpFieldName]=%7B%7D&distributionProfile[submitAction][httpFileName]=%7B%7D&distributionProfile[submitAction][password]=%7B%7D&distributionProfile[submitAction][protocol]=%7B%7D&distributionProfile[submitAction][serverPath]=%7B%7D&distributionProfile[submitAction][serverUrl]=%7B%7D&distributionProfile[submitAction][username]=%7B%7D&distributionProfile[submitEnabled]=%7B%7D&distributionProfile[sunriseDefaultOffset]=%7B%7D&distributionProfile[sunsetDefaultOffset]=%7B%7D&distributionProfile[tags]=%7B%7D&distributionProfile[targetAccountId]=%7B%7D&distributionProfile[targetLoginId]=%7B%7D&distributionProfile[targetLoginPassword]=%7B%7D&distributionProfile[targetServiceUrl]=%7B%7D&distributionProfile[target]=%7B%7D&distributionProfile[thumbnailAssetFilenameXslt]=%7B%7D&distributionProfile[ugcPolicy]=%7B%7D&distributionProfile[updateEnabled]=%7B%7D&distributionProfile[upstreamNetworkId]=%7B%7D&distributionProfile[upstreamNetworkName]=%7B%7D&distributionProfile[upstreamVideoId]=%7B%7D&distributionProfile[urgentReference]=%7B%7D&distributionProfile[useCategoryEntries]=%7B%7D&distributionProfile[userAccessToken]=%7B%7D&distributionProfile[username]=%7B%7D&distributionProfile[user]=%7B%7D&distributionProfile[videoMediaType]=%7B%7D&distributionProfile[wmvFlavorParamsId]=%7B%7D&distributionProfile[xsltFile]=%7B%7D&distributionProfile[xsl]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update Distribution Profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "99d2793c-c111-4a69-9b59-cb13d2e06ea1"
            }
          ]
        },
        {
          "id": "a0e5eb5e-df2c-4030-839a-8c2ba29f52df",
          "name": "distributionProfile.updateStatus",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_distributionprofile/action/updateStatus?id=%7B%7D&No Name=%7B%7D&status=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update Distribution Profile status by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c5fc64e6-bc34-4d44-9c01-68bfd7df92ab"
            }
          ]
        },
        {
          "id": "dc34f620-e25b-429b-945c-7c474383cb76",
          "name": "distributionProvider.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_distributionprovider/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[isDefaultEqual]=%7B%7D&filter[isDefaultIn]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[partnerIdEqual]=%7B%7D&filter[partnerIdIn]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[typeEqual]=%7B%7D&filter[typeIn]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List all distribution providers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "361e6297-feb3-434b-9e22-860a21abe695"
            }
          ]
        },
        {
          "id": "8304f6f8-14ba-4d35-9d7c-20ea3d127be5",
          "name": "entryDistribution.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/add?entryDistribution[assetIds]=%7B%7D&entryDistribution[distributionProfileId]=%7B%7D&entryDistribution[entryId]=%7B%7D&entryDistribution[flavorAssetIds]=%7B%7D&entryDistribution[sunrise]=%7B%7D&entryDistribution[sunset]=%7B%7D&entryDistribution[thumbAssetIds]=%7B%7D&entryDistribution[validationErrors]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add new Entry Distribution"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e2252f9-79a0-4d64-8eb6-413ab1c60c14"
            }
          ]
        },
        {
          "id": "ad02f70a-1cba-469b-acb2-7ed702af4fd2",
          "name": "entryDistribution.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/delete?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete Entry Distribution by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5b5a9bf5-5cbb-4fe5-a0c6-e5b573266c00"
            }
          ]
        },
        {
          "id": "1cc3a1bd-3ba5-4a2f-83e2-5353e89417d4",
          "name": "entryDistribution.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Entry Distribution by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "036f4957-4e2d-446e-91a8-be536ee3904b"
            }
          ]
        },
        {
          "id": "21786abe-a003-4c80-824b-e5dd07892e31",
          "name": "entryDistribution.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[dirtyStatusEqual]=%7B%7D&filter[dirtyStatusIn]=%7B%7D&filter[distributionProfileIdEqual]=%7B%7D&filter[distributionProfileIdIn]=%7B%7D&filter[entryIdEqual]=%7B%7D&filter[entryIdIn]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[orderBy]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[submittedAtGreaterThanOrEqual]=%7B%7D&filter[submittedAtLessThanOrEqual]=%7B%7D&filter[sunriseGreaterThanOrEqual]=%7B%7D&filter[sunriseLessThanOrEqual]=%7B%7D&filter[sunsetGreaterThanOrEqual]=%7B%7D&filter[sunsetLessThanOrEqual]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List all distribution providers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f4167ad0-646d-4f67-a6e0-1b6c8df5fdaf"
            }
          ]
        },
        {
          "id": "5bde377c-b204-4969-a810-1665993d9ec4",
          "name": "entryDistribution.retrySubmit",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/retrySubmit?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retries last submit action"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "523e841e-fe16-48f5-aaa0-b073c7902bbb"
            }
          ]
        },
        {
          "id": "319612a9-98ff-42b1-8177-b70e77771b72",
          "name": "entryDistribution.serveReturnedData",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/serveReturnedData?actionType=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Serves entry distribution returned data"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f73aba8c-5dab-4b99-b8ca-b89abc0d94bd"
            }
          ]
        },
        {
          "id": "0dbb6e1f-da34-445d-8d63-659e79849756",
          "name": "entryDistribution.serveSentData",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/serveSentData?actionType=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Serves entry distribution sent data"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b3901f1d-9411-4a54-9ef9-5014a1bff082"
            