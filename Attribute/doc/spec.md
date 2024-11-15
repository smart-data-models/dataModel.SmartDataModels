<!-- 10-Header -->
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  

=================
<!-- 15-License -->


<!-- /15-License -->
<!-- 20-Description -->
<!-- /20-Description -->
<!-- 30-PropertiesList -->




<!-- /30-PropertiesList -->
<!-- 35-RequiredProperties -->

- No required properties  
<!-- 40-NotesYaml -->

<!-- /40-NotesYaml -->
<!-- 50-DataModelHeader -->


<!-- /50-DataModelHeader -->
<!-- 60-ModelYaml -->
<details><summary><strong>full yaml details</strong></summary>    

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



<details><summary><strong>show/hide example</strong></summary>    


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


<details><summary><strong>show/hide example</strong></summary>    


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


<details><summary><strong>show/hide example</strong></summary>    


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


<details><summary><strong>show/hide example</strong></summary>    


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

<!-- /95-Units -->
<!-- 97-LastFooter -->
---  
