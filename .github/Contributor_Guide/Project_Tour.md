# Project Tour

In the 'lib' folder you will find three forlders-models,screens and widgets, and a main.dart file.
All the changes to be made are to be made in the files of 'lib' folder.
'screens' folder has three files with '.dart' extension.'models' folder has one file with '.dart' extension.'widgets' folder has one file with '.dart' extension.All bug fixes, enhancements, modification of code are to be done in these files.

If you want to change any dependencies then it has to be done in the 'pubspec.yaml' file.


C:.
|   .gitignore
|   CODE_OF_CONDUCT.md
|   commitlint.config.js
|   package-lock.json
|   package.json
|   README.md
    pubspec.lock
    pubspec.yaml
    roll_dice_app.iml
    analysis_options.yaml
    .metadata
|
+---.github
|   +---Contributor_Guide
|   |       commiting.md
|   |       Contributing.md
|   |       Project_Tour.md
|   |
|   +---ISSUE_TEMPLATE
|   |       bug_report.yaml
|   |       feature_request.yaml
|   |
|   +---PULL_REQUEST_TEMPLATE
|   |       pr.md
|   |
|   \---workflows
|           commitlint.yaml
|           prmerged.yaml
|
+---.husky
|       commit-msg
|       pre-commit
|
+---lib
    +---models
           note_model.dart
    +---screens
           create_note.dart
           home_screen.dart
           notes_view.dart
    +---widgets
           note_card.dart             
    main.dart