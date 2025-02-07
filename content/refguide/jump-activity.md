---
title: "Jump"
parent: "workflows"
menu_order: 35
tags: ["workflow", "workflows", "jump", "Studio Pro"]
---

## 1 Introduction

The **Jump** activity allows you to jump to other activities in the workflow. This is useful when, for example, you are approving a request and need more details that are provided in one of the previous user tasks:

![Jump Example](attachments/jump-activity/jump-activity.jpg)

## 2 Properties

The Jump activity properties consist of the **General** section.

### 2.1 Name

**Name** is the internal name of the element. When referring to the element in the app project you will use this name. It must be unique within the workflow, but you can have two elements with the same name in different workflows. 

### 2.2 Caption

The **Caption** describes what happens in this element. It is displayed in the workflow element to make the workflow easier to read and understand without needing to add annotations.

### 2.3 Target

**Target** is the activity that the workflow process will jump to during execution. You can select the activity you would like to go to from the drop-down menu. 

{{% alert type="warning" %}}
You cannot use the **Jump** activity in a [Parallel split](parallel-split) or in a path where it would end the workflow without any other path continuing it. 
{{% /alert %}}

## 3 Read More

* [Workflow Properties](workflow-properties)