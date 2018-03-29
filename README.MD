#Amazing web application sample with Vue.js + Vuetify + Python(django)

## Running in Production

- Open GCP console
- Go to Compute Engine
- Click in bmind-intelligent-catalog-vm VM Instance
- Click in SSH to open more options
- Select "View gcloud command"
- In the modal, select RUN IN CLOUD SHELL  (Will open a window in the browser)

- Go to directory `bmind-intelligent-catalog-web-vm:/home/bmind/DataViz$`
- Run the follow command to up the Django Server

`sudo python3 manage.py runserver 10.158.0.2:80'`


## Getting Started

This repository is to develop our offer codename Intelligent Catalog used by Via Varejo and Dotz

Intelligent Catalog bMind service codename is used to support and help data scientists and DBAs to create an unique data repository using Artificial Intelligence techniques to group, link and deduplicate data.

### Steps
- Landing Zone: raw data, all data as they are
- Sensitive Zone: information with security and restritive access
- Working Zone: human interaction to work, link and audit results from bMind processing
- Golden Zone: The final goal, a data catalog cleaned, deduped and ready to use through our APIs

### Folder Structure

Describe here how will be our folder structure
- folder 1: Contains all templates
- folder 2: Contains all components to support operation
- folder 3: Contains all scripts and 3d party components



