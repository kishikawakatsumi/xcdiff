# Command
```json
["-p1", "{ios_project_1}", "-p2", "{ios_project_2}", "-g", "resources", "-f", "markdown", "-v"]
```

# Expected exit code
1

# Expected output
```

## ❌ RESOURCES > "Project" target


### ⚠️  Only in first (2):

  - `/Project/Group B/AViewController.xib`
  - `/Project/Resources/time.png`



## ✅ RESOURCES > "ProjectFramework" target


## ❌ RESOURCES > "ProjectTests" target


### ⚠️  Only in second (1):

  - `/ProjectTests/Responses/ListResponse.json`



## ❌ RESOURCES > "ProjectUITests" target


### ⚠️  Only in first (1):

  - `/ProjectUITests/Screenshots/empty.png`




```