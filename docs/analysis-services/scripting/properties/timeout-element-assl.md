---
title: "Timeout Element (ASSL) | Microsoft Docs"
ms.custom: ""
ms.date: "03/06/2017"
ms.prod: analysis-services
ms.prod_service: "analysis-services"
ms.component: ""
ms.reviewer: ""
ms.suite: "pro-bi"
ms.technology: 
  

ms.tgt_pltfrm: ""
ms.topic: "reference"
apiname: 
  - "Timeout Element"
apilocation: 
  - "http://schemas.microsoft.com/analysisservices/2003/engine"
apitype: "Schema"
applies_to: 
  - "SQL Server 2016 Preview"
f1_keywords: 
  - "Timeout"
helpviewer_keywords: 
  - "Timeout element"
ms.assetid: 7694872b-bd05-459f-b5dc-3cfbd92a9664
caps.latest.revision: 35
author: "Minewiskan"
ms.author: "owend"
manager: "kfile"
---
# Timeout Element (ASSL)
[!INCLUDE[ssas-appliesto-sqlas](../../../includes/ssas-appliesto-sqlas.md)]
  Specifies the time, in seconds, after which an attempt to retrieve data reports a timeout.  
  
## Syntax  
  
```xml  
  
<DataSource>  
   ...  
   <Timeout>...</Timeout>  
   ...  
</DataSource>  
```  
  
## Element Characteristics  
  
|Characteristic|Description|  
|--------------------|-----------------|  
|Data type and length|Duration|  
|Default value|None|  
|Cardinality|0-1: Optional element that can occur once and only once.|  
  
## Element Relationships  
  
|Relationship|Element|  
|------------------|-------------|  
|Parent element|[DataSource](../../../analysis-services/scripting/objects/datasource-element-assl.md)|  
|Child elements|None|  
  
## Remarks  
 The element that corresponds to the parent of **Timeout** in the Analysis Management Objects (AMO) object model is <xref:Microsoft.AnalysisServices.DataSource>.  
  
## See Also  
 [Properties &#40;ASSL&#41;](../../../analysis-services/scripting/properties/properties-assl.md)  
  
  
