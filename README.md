# Role: Apache  
This repository contains a simple and functional Ansible role for setting up an Apache web server.  

---

## 📁 Role Structure  

The directory structure of the `apache` role is as follows:

```plaintext
apache/
├── tasks/
│   └── main.yml         # Main tasks to install and configure Apache
├── handlers/
│   └── main.yml         # Handlers to manage Apache services
├── templates/           # Directory for Jinja2 templates (optional)
├── files/               # Static files like index.html
├── vars/
│   └── main.yml         # Role-specific variables
├── defaults/
│   └── main.yml         # Default variables with the lowest priority
├── meta/
│   └── main.yml         # Role metadata and dependencies
└── README.md            # Documentation for the role

