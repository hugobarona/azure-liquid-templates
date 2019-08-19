# Liquid Templates for Azure Monitor

## What is this?
This is a repo to store liquid templates that can be stored in the Azure Integration accounts and be used on Azure Logic Apps to transform and parse JSON objects.

## Files
- **commonAlertSchema.liquid:** This template is used to parse an object using the Azure Monitor Common Alert Schema. This is useful if you have multiple alerts configured on Azure, and you are using Action Groups with actions to call Logic Apps, so you can activate them to use the Common Schema Alert, and they will all use the same schema, independently of its type (metric, log, etc.)


