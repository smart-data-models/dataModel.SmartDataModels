<!-- 10-Header -->  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  
实体：属性  
=====<!-- /10-Header -->  
<!-- 15-License -->  
[开放许可](https://github.com/smart-data-models//dataModel.SmartDataModels/blob/master/Attribute/LICENSE.md)  
[文件自动生成](https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->  
<!-- 20-Description -->  
<!-- /20-Description -->  
<!-- 30-PropertiesList -->  

## 属性列表  

<sup><sub>[*] 如果属性中没有类型，是因为它可能有多个类型或不同的格式/模式</sub></sup>。  
<!-- /30-PropertiesList -->  
<!-- 35-RequiredProperties -->  
所需属性  
- 无必要属性  <!-- /35-RequiredProperties -->  
<!-- 40-NotesYaml -->  
这是智能数据模型倡议的数据模型属性模型 https://smartdatamodels.org，您可以从 https://smartdatamodels.org/extra/smartdatamodels.json 下载全部内容。  
<!-- /40-NotesYaml -->  
<!-- 50-DataModelHeader -->  
## 属性的数据模型描述  
按字母顺序排列（点击查看详情）  
<!-- /50-DataModelHeader -->  
<!-- 60-ModelYaml -->  
<details><summary><strong>full yaml details</strong></summary>    
```yaml  
Attribute:    
  description: 'Description of the data model Attribute '    
  properties:    
    _id:    
      description: Identifier of the item given from mongodb by default    
      type: string    
      x-ngsi:    
        type: Property    
    context:    
      description: Context url of the attribute    
      type: string    
      x-ngsi:    
        type: Property    
    dataModel:    
      description: The data model this attribute belongs to    
      type: string    
      x-ngsi:    
        type: Property    
    dataType:    
      description: 'Json schema basic data type, boolean, integer, number, string, object or array'    
      type: string    
      x-ngsi:    
        type: Property    
    description:    
      description: Textual description of the attribute    
      type: string    
      x-ngsi:    
        type: Property    
    format:    
      description: 'Either date, or time, or date-time, or URI, etc the format of the attribute according to the definitions in json schema'    
      type: string    
      x-ngsi:    
        type: Property    
    id:    
      description: "Designed identifier of the attribute in the format of its context plus the version number, such as https://smartdatamodels.org/dataModel.EnergyCIM/WindGenType4IEC/address/addressLocality#0.0.1"    
      type: string    
      x-ngsi:    
        type: Property    
    license:    
      description: Link to the license for the data model    
      type: string    
      x-ngsi:    
        type: Property    
    model:    
      description: Optional descriptor pointing to the semantic source of the attribute    
      type: string    
      x-ngsi:    
        type: Property    
    modelTags:    
      description: Tags of the data model    
      type: string    
      x-ngsi:    
        type: Property    
    parentContext:    
      description: Id of the parent attribute of the current one if it has any    
      type: string    
      x-ngsi:    
        type: Property    
    parentId:    
      description: Identifier of the parent attribute of the current one if it has any    
      type: string    
      x-ngsi:    
        type: Property    
    property:    
      description: Name of the attribute    
      type: string    
      x-ngsi:    
        type: Property    
    repoName:    
      description: The subject this attribute belongs to    
      type: string    
      x-ngsi:    
        type: Property    
    schemaVersion:    
      description: Version of the data model    
      type: string    
      x-ngsi:    
        type: Property    
    subpropertiesContext:    
      description: Id of the subattributes of the current one if it has any    
      items:    
        description: Every id of the subattributes of the current one if it has any    
        type: string    
        x-ngsi:    
          type: Property    
      type: array    
      x-ngsi:    
        type: Property    
    type:    
      description: It must be equal to `ThreePhaseAcMeasurement`.    
      enum:    
        - Attribute    
      type: string    
      x-ngsi:    
        type: Property    
    typeNGSI:    
      description: 'Whether it is a Property, GeoProperty, or Relationship according to the NGSI standard. Other types could be as well'    
      type: string    
      x-ngsi:    
        type: Property    
    units:    
      description: Optional descriptor with the units. Preferably in UNECE format    
      type: string    
      x-ngsi:    
        type: Property    
  required:    
    - id    
    - type    
  type: object    
  x-derived-from: ""    
  x-disclaimer: 'Redistribution and use in source and binary forms, with or without modification, are permitted  provided that the license conditions are met. Copyleft (c) 2024 Contributors to Smart Data Models Program'    
  x-license-url: https://github.com/smart-data-models/dataModel.SmartDataModels/blob/master/Attribute/LICENSE.md    
  x-model-schema: https://smart-data-models.github.io/dataModel.SmartDataModels/Attribute/schema.json    
  x-model-tags: ""    
  x-version: 0.0.1    
```  
</details>    
<!-- /60-ModelYaml -->  
<!-- 70-MiddleNotes -->  
<!-- /70-MiddleNotes -->  
<!-- 80-Examples -->  
## 有效载荷示例  
#### 属性 NGSI-v2 键值示例  
下面是一个以 JSON-LD 格式作为键值的属性示例。当使用 `options=keyValues` 时，这与 NGSI-v2 兼容，并返回单个实体的上下文数据。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "_id": "6557985a8f4f3ce5fd4e87df",  
  "id": "https://smartdatamodels.org/dataModel.Hl7/Account/_valueDate/extension#0.0.1",  
  "type": "Attribute",  
  "parentContext": "https://smartdatamodels.org/dataModel.Hl7/_valueDate",  
  "parentId": "https://smartdatamodels.org/dataModel.Hl7/Account/_valueDate#0.0.1",  
  "context": "https://smartdatamodels.org/dataModel.Hl7/extension",  
  "property": "extension",  
  "dataModel": "Account",  
  "repoName": "dataModel.Hl7",  
  "modelTags": "HL7",  
  "license": "https://github.com/smart-data-models/dataModel.Hl7/blob/master/Account/LICENSE.md",  
  "schemaVersion": "0.0.1",  
  "dataType": "array",  
  "description": "May be used to represent additional information that is not part of the basic definition of the element. To make the use of extensions safe and manageable, there is a strict set of governance  applied to the definition and use of extensions. Though any implementer can define an extension, there is a set of requirements that SHALL be met as part of the definition of the extension"  
}  
```  
</details>  
#### 属性 NGSI-v2 标准化示例  
下面是一个规范化 JSON-LD 格式的属性示例。在不使用选项的情况下，它与 NGSI-v2 兼容，并返回单个实体的上下文数据。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "https://smartdatamodels.org/dataModel.Hl7/Account/_valueDate/extension#0.0.1",  
  "type": "Attribute",  
  "_id": {  
    "type": "Text",  
    "value": "6557985a8f4f3ce5fd4e87df"  
  },  
  "parentContext": {  
    "type": "Text",  
    "value": "https://smartdatamodels.org/dataModel.Hl7/_valueDate"  
  },  
  "parentId": {  
    "type": "Text",  
    "value": "https://smartdatamodels.org/dataModel.Hl7/Account/_valueDate#0.0.1"  
  },  
  "context": {  
    "type": "Text",  
    "value": "https://smartdatamodels.org/dataModel.Hl7/extension"  
  },  
  "property": {  
    "type": "Text",  
    "value": "extension"  
  },  
  "dataModel": {  
    "type": "Text",  
    "value": "Account"  
  },  
  "repoName": {  
    "type": "Text",  
    "value": "dataModel.Hl7"  
  },  
  "modelTags": {  
    "type": "Text",  
    "value": "HL7"  
  },  
  "license": {  
    "type": "Text",  
    "value": "https://github.com/smart-data-models/dataModel.Hl7/blob/master/Account/LICENSE.md"  
  },  
  "schemaVersion": {  
    "type": "Text",  
    "value": "0.0.1"  
  },  
  "dataType": {  
    "type": "Text",  
    "value": "array"  
  },  
  "description": {  
    "type": "Text",  
    "value": "May be used to represent additional information that is not part of the basic definition of the element. To make the use of extensions safe and manageable, there is a strict set of governance  applied to the definition and use of extensions. Though any implementer can define an extension, there is a set of requirements that SHALL be met as part of the definition of the extension"  
  }  
}  
```  
</details>  
#### 属性 NGSI-LD 键值示例  
下面是一个以 JSON-LD 格式作为键值的属性示例。当使用 `options=keyValues` 时，这与 NGSI-LD 兼容，并返回单个实体的上下文数据。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "_id": "6557985a8f4f3ce5fd4e87df",  
  "id": "https://smartdatamodels.org/dataModel.Hl7/Account/_valueDate/extension#0.0.1",  
  "type": "Attribute",  
  "parentContext": "https://smartdatamodels.org/dataModel.Hl7/_valueDate",  
  "parentId": "https://smartdatamodels.org/dataModel.Hl7/Account/_valueDate#0.0.1",  
  "context": "https://smartdatamodels.org/dataModel.Hl7/extension",  
  "property": "extension",  
  "dataModel": "Account",  
  "repoName": "dataModel.Hl7",  
  "modelTags": "HL7",  
  "license": "https://github.com/smart-data-models/dataModel.Hl7/blob/master/Account/LICENSE.md",  
  "schemaVersion": "0.0.1",  
  "dataType": "array",  
  "description": "May be used to represent additional information that is not part of the basic definition of the element. To make the use of extensions safe and manageable, there is a strict set of governance  applied to the definition and use of extensions. Though any implementer can define an extension, there is a set of requirements that SHALL be met as part of the definition of the extension",  
  "@context": [  
    "https://raw.githubusercontent.com/smart-data-models/dataModel.SmartDataModels/refs/heads/master/context.jsonld"  
  ]  
}  
```  
</details>  
#### 属性 NGSI-LD 标准化示例  
下面是一个规范化 JSON-LD 格式的属性示例。当不使用选项时，它与 NGSI-LD 兼容，并返回单个实体的上下文数据。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsild:https://smartdatamodels.org/dataModel.Hl7/Account/_valueDate/extension#0.0.1",  
  "type": "Attribute",  
  "_id": {  
    "type": "Property",  
    "value": "6557985a8f4f3ce5fd4e87df"  
  },  
  "parentContext": {  
    "type": "Property",  
    "value": "https://smartdatamodels.org/dataModel.Hl7/_valueDate"  
  },  
  "parentId": {  
    "type": "Property",  
    "value": "https://smartdatamodels.org/dataModel.Hl7/Account/_valueDate#0.0.1"  
  },  
  "context": {  
    "type": "Property",  
    "value": "https://smartdatamodels.org/dataModel.Hl7/extension"  
  },  
  "property": {  
    "type": "Property",  
    "value": "extension"  
  },  
  "dataModel": {  
    "type": "Property",  
    "value": "Account"  
  },  
  "repoName": {  
    "type": "Property",  
    "value": "dataModel.Hl7"  
  },  
  "modelTags": {  
    "type": "Property",  
    "value": "HL7"  
  },  
  "license": {  
    "type": "Property",  
    "value": "https://github.com/smart-data-models/dataModel.Hl7/blob/master/Account/LICENSE.md"  
  },  
  "schemaVersion": {  
    "type": "Property",  
    "value": "0.0.1"  
  },  
  "dataType": {  
    "type": "Property",  
    "value": "array"  
  },  
  "description": {  
    "type": "Property",  
    "value": "May be used to represent additional information that is not part of the basic definition of the element. To make the use of extensions safe and manageable, there is a strict set of governance  applied to the definition and use of extensions. Though any implementer can define an extension, there is a set of requirements that SHALL be met as part of the definition of the extension"  
  },  
  "@context": [  
    "https://raw.githubusercontent.com/smart-data-models/dataModel.SmartDataModels/refs/heads/master/context.jsonld"  
  ]  
}  
```  
</details><!-- /80-Examples -->  
<!-- 90-FooterNotes -->  
<!-- /90-FooterNotes -->  
<!-- 95-Units -->  
请参阅 [FAQ 10](https://smartdatamodels.org/index.php/faqs/)，获取如何处理幅度单位的答案。  
<!-- /95-Units -->  
<!-- 97-LastFooter -->  
---  
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->  
