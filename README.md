Gitflow Workflow Architecture
 Main Branches:
   main: This branch contains the production-ready code. Releases are tagged here.
   develop: This branch contains the latest delivered development changes for the next release.
  Supporting Branches:
    feature/*: Branches created from develop for new features.
    release/*: Branches created from develop when preparing for a new release.
    hotfix/*: Branches created from main to quickly fix production issues
Pseudo Code Files and Branches
  # Main Branch (production-ready code)
  # Files: app.py, config.py, ...
  
  # Develop Branch (main development branch)
  # Files: app.py, config.py, new_feature.py, ...
  
  # Release Branch (for the month of January)
  # Files: app.py, config.py, new_feature.py, bugfix_1.py, ...
  
  # Hotfix Branch (for a critical bug in production)
  # Files: app.py, config.py, ...
