# python-mongo-interview

# Setup

# Collections

components
templates

# How to Prep.

## - Start a local version of Mongo DB

## - Insert the components.json and template.json into the 2 collections

## - Install Pymongo and any tooling of your choice in a python environment

#

#

# What you need to achieve

# Task 1

## Generate a key for every item templates.fields that uses name and replace spaces with underscores

## Update all the fields in templates with their key in the mongo db

#

# Task 2

# For Every Item in components.templateData. Insert a new object on the _components_ collection called **templateFieldData** and consists of the key from template.fields matching the templateFieldId in templateData.

# Example of final result

## templates

```
{
    "fields":[{
        "name":"General 12 3",
        "key":"general_12_3",
        "_id":ObjectId("6653e7a07033119395c06638")
    }]
}
```

## components

```
{
    "templateData": [{
        "value":"1",
        "templateFieldId":ObjectId("6653e73b388b7e4da37021d8"),
        "_id":ObjectId("6653e74afc50b8337c82f97f")
    }],
    "templateFieldData":{
        "general_12_3":"1"
    }
}
```

# Bonus points if this tool can be used a cli tool
