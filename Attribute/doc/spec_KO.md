<!-- 10-Header -->  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  
엔티티: 속성  
=======<!-- /10-Header -->  
<!-- 15-License -->  
[오픈 라이선스](https://github.com/smart-data-models//dataModel.SmartDataModels/blob/master/Attribute/LICENSE.md)  
[문서 자동 생성](https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->  
<!-- 20-Description -->  
글로벌 설명: 데이터 모델 속성 설명 ** **  
버전: 0.0.1  
<!-- /20-Description -->  
<!-- 30-PropertiesList -->  

## 속성 목록  

<sup><sub>[*] 속성에 유형이 없는 것은 여러 유형 또는 다른 형식/패턴을 가질 수 있기 때문입니다</sub></sup>.  
- `_id[string]`: 기본적으로 mongodb에서 제공된 항목의 식별자  - `context[string]`: 속성의 컨텍스트 URL  - `dataModel[string]`: 이 속성이 속한 데이터 모델  - `dataType[string]`: Json 스키마 기본 데이터 유형, 부울, 정수, 숫자, 문자열, 객체 또는 배열  - `description[string]`: 속성에 대한 텍스트 설명  - `format[string]`: 날짜, 시간, 날짜-시간, URI 등 json 스키마의 정의에 따른 속성의 형식입니다.  - `id[string]`: 컨텍스트 형식에 버전 번호가 더해진 속성의 설계 식별자(예: https://smartdatamodels.org/dataModel.EnergyCIM/WindGenType4IEC/address/addressLocality#0.0.1)  - `license[string]`: 데이터 모델 라이선스 링크  - `model[string]`: 속성의 의미적 출처를 가리키는 선택적 설명자(선택 사항)  - `modelTags[string]`: 데이터 모델의 태그  - `parentContext[string]`: 현재 속성이 있는 경우 현재 속성의 부모 속성의 ID입니다.  - `parentId[string]`: 현재 속성이 있는 경우 현재 속성의 부모 속성의 식별자입니다.  - `property[string]`: 속성 이름  - `repoName[string]`: 이 속성이 속한 주제  - `schemaVersion[string]`: 데이터 모델 버전  - `subpropertiesContext[array]`: 현재 속성의 하위 속성이 있는 경우 해당 속성의 ID입니다.  - `type[string]`: 이 값은 `ThreePhaseAcMeasurement`와 같아야 합니다.  - `typeNGSI[string]`: NGSI 표준에 따른 속성, 지오프로퍼티 또는 관계인지 여부입니다. 다른 유형도 가능합니다.  - `units[string]`: 단위와 함께 선택적 설명자. 가급적 UNECE 형식이 좋습니다.  <!-- /30-PropertiesList -->  
<!-- 35-RequiredProperties -->  
필수 속성  
- `id`  - `type`  <!-- /35-RequiredProperties -->  
<!-- 40-NotesYaml -->  
스마트 데이터 모델 이니셔티브의 데이터 모델 속성에 대한 모델입니다 https://smartdatamodels.org https://smartdatamodels.org/extra/smartdatamodels.json 에서 모두 다운로드할 수 있습니다.  
<!-- /40-NotesYaml -->  
<!-- 50-DataModelHeader -->  
## 속성에 대한 데이터 모델 설명  
알파벳순으로 정렬(자세한 내용을 보려면 클릭)  
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
## 페이로드 예시  
#### 속성 NGSI-v2 키-값 예시  
다음은 키 값으로 JSON-LD 형식의 속성 예시입니다. 이는 `옵션=키값`을 사용할 때 NGSI-v2와 호환되며 개별 엔티티의 컨텍스트 데이터를 반환합니다.  
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
#### 속성 NGSI-v2 정규화 예제  
다음은 정규화된 JSON-LD 형식의 속성 예시입니다. 이는 옵션을 사용하지 않을 때 NGSI-v2와 호환되며 개별 엔티티의 컨텍스트 데이터를 반환합니다.  
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
#### 속성 NGSI-LD 키-값 예시  
다음은 키 값으로 JSON-LD 형식의 속성 예시입니다. 이는 `옵션=키값`을 사용할 때 NGSI-LD와 호환되며 개별 엔티티의 컨텍스트 데이터를 반환합니다.  
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
#### 속성 NGSI-LD 정규화 예제  
다음은 정규화된 JSON-LD 형식의 속성 예시입니다. 이는 옵션을 사용하지 않을 때 NGSI-LD와 호환되며 개별 엔티티의 컨텍스트 데이터를 반환합니다.  
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
규모 단위를 다루는 방법에 대한 답변은 [FAQ 10](https://smartdatamodels.org/index.php/faqs/)을 참조하세요.  
<!-- /95-Units -->  
<!-- 97-LastFooter -->  
---  
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->  
