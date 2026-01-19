<!-- ALL-CONTRIBUTORS-LIST:END -->


# Create your first custom AppStore for ZimaOS

The quickest way to create your own AppStore, is simply forking an existing AppStore and trim all the apps and unneccessary files before adding your own.

There are few AppStores listed at Store list, you can choose one of them to fork.

# Prerequisites

You should be comfortable about repository forking and pushing commits on GitHub before proceeding to the steps.

# Steps

# Step 1 - Fork an AppStore

In the steps below, we will start by forking the official CasaOS AppStore.

    Go to https://github.com/iceWhaleTech/CasaOS-AppStore

    and click the Fork button on the top right corner. If everything looks good, click on Create Fork button. Wait until the forked repository is ready

# Step 2 - Cleanup the forked repository

    Hit the [.] key to open the repository in an online IDE.

    Remove all folders, but keep the Apps folder

    Remove all subfolders in the Apps folder, but you can keep one subfolder as a template.

    Remove all files, but the following files are optional to keep:
        category-list.json (category list along with description)
        recommend-list.json (featured apps as seen in the CasaOS AppStore UI)
        CONTRIBUTING.md (guidelines for creating an app)

# Step 3 - Add the first app

    Follow the CONTRIBUTING.md to add your first app to the Apps folder.

        You can use the existing app in the Apps folder as a template.

    Once you are done, push the changes.

# Step 4 - Test the AppStore

    Go back to the GitHub repository page at step 3 above.
    Click on the <> Code dropdown menu
    Copy the URL of Download ZIP
    Go to AppStore UI in CasaOS, and click on + Add Source
    Paste the URL then click on Add +
    Wait until the app from your AppStore shows up


## 3-Party AppStores

# I'm no developer. Just an old man getting a grasp of tech. I just follow youtube videos.
