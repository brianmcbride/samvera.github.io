---
title: "Creating a Work"
permalink: create-works-2.0.html
folder: samvera/manager_guide/create-works-2.0.md
sidebar: home_sidebar
a-z: ['manager_guide', 'user_guide']
keywords: Best Practices, managers, repo mangers, hyrax administration
tags: [user_resources]
categories: How to use the Administration panel in hyrax
version:
  id: 'hyrax_2.0-master'
  versions:  
  - label: 'Hyrax 1.0'
    link:  'create-works-1.0.html'
  - label: 'Hyrax 2.0'
    link:  'create-works-2.0.html'
    selected: 'true'
---

*This Guide is maintained by Samvera's [Repository Management Interest Group](https://wiki.duraspace.org/display/samvera/Repository+Management+Interest+Group). Screenshots are taken from [Nurax](https://nurax.curationexperts.com/), a testing repository running on the latest release of Hyrax. Hosting is generously provided by [Data Curation Experts](https://curationexperts.com/). Please open an issue on our [GitHub repository](https://github.com/samvera/samvera.github.io) to request edits or additions.*

# Creating a Work

Works are items in the repository, containing files and metadata. Works are presented as one intellectual object. Example: A single dissertation (PDF and metadata), a dataset containing multiple files (spreadsheets, images, text files and metadata).

A user must be logged in to create a Work. There are several ways to add a new work:

- On the homepage, click "Share Your Work"
- From the Dashboard, click on the "Works" sub-heading, click "Add new work"

If your repository contains more than one work type, you will need to select the work type to proceed. Work types allow repository managers to create separate deposit forms based on the type of work, such as Dissertations, Images, or Datasets. Each work type might have specific metadata requirements or deposit instructions.

![Add New Generic Work](images\screenshots\user-addgenericwork-2.png)

There three tabs in the Add New Work interface: “Description”, “Files”, and “Relationships”. In order for the work to be deposited, a work must minimally have: the required description fields filled out, at least one file uploaded, and the deposit agreement checkbox checked. Once these required items are completed, the depositor must click “Save” in order to deposit the work. Navigating away from the deposit screen before clicking save causes user to have to redo deposit.

## Description (required)
The “Description” tab is for adding descriptive metadata. Fill out the fields marked “Required”. Clicking “Additional Fields” will show more metadata fields, which are optional. Customizing fields is possible by creating a new Work Type.

## Files (required)
![Add New Generic Work | Files](images\screenshots\user-addnewgenericwork-files-2.png)

The “Files” tab is for uploading files, either locally or from a cloud service (e.g. DropBox, Google Drive, Box.com, etc.). You can browse local files to upload, or drag and drop files from your desktop. If your repository is configured to interact with a cloud service, users can click “Browse cloud files” and securely connect to their own Dropbox. They can then browse cloud files to upload. Files can also be removed from the deposit in the “Files” tab.

## Relationships (optional)
![Add New Generic Work | Relationships](images\screenshots\user-addnewgenericwork-relationships.png)

The “Relationships” tab lets you add the work to an Administrative Set or a Collection. Administrative users can add a work to any Administrative Set or Collection in the repository. Regular users are only able to add works to Collections that they have created or collections for which they have been granted a depositor/manager role. The Administrative Set and Collections fields will be automaticall populated with options to which the user has depositor access.

## Visibility
You can select one of five options for visibility: Public, Your Institution, Embargo, Lease, Private. If you are not seeing five visibility options, it is likely that your work is set to deposit to an administrative set with fewer visibility options than the default. Visibility only controls who can view or download your work -- it does not control edit access.

- Public makes the work available to the general public. Metadata is available to be crawled by search engines for discovery.
- Institution restricts access to works and work metadata to users with login privileges. Users will need to be logged into the repostory to access the work.
- Embargo lets you restrict access to Private or Institution until a specified date, when it will be opened to the public or your institution
- Lease permits access to the work to the public or Institution until a specified date, when it will be restricted to Private or your institution

## Deposit Agreement (required)
The depositor must check the deposit agreement checkbox in order to deposit. The agreement can be customized by repository administrators by going to the Dashboard, and editing the Deposit Agreement from the Pages panel.

## Depositing as a proxy
Users can designate other users of the system to deposit on their behalf by visiting their dashboard. Once someone has been set as a proxy for another user, the sidebar will offer the option to deposit on behalf of yourself or the other user. If you deposit on behalf of another user, the ownership of the work will automatically be transferred to that user when the deposit completes.
