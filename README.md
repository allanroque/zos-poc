# **Ansible Collections Local Setup**

Este documento descreve a estrutura de diretórios e as coleções Ansible instaladas localmente no diretório `./collections`. Este repositório pode ser usado para gerenciar e executar playbooks com coleções específicas.

---

## **Estrutura de Diretórios**

A seguir está a estrutura básica do diretório, incluindo as coleções instaladas:

```plaintext
collections/
├── ansible_collections/
│   ├── amazon/
│   │   └── aws/
│   ├── ansible/
│   │   └── utils/
│   ├── community/
│   │   └── general/
│   ├── ibm/
│   │   ├── ibm_zos_core/
│   │   ├── ibm_zos_cics/
│   │   ├── ibm_zos_ims/
│   │   └── ibm_zosmf/
│   └── servicenow/
│       └── itsm/
├── amazon.aws-9.1.1.info
├── ansible.utils-5.1.2.info
├── community.general-10.2.0.info
├── ibm.ibm_zos_cics-2.1.0.info
├── ibm.ibm_zos_core-1.12.0.info
├── ibm.ibm_zos_ims-1.3.0.info
├── ibm.ibm_zosmf-1.5.0.info
└── servicenow.itsm-2.7.0.info

## **Coleções Instaladas**

As seguintes coleções foram instaladas localmente usando o `ansible-galaxy`:

### **IBM**
- **ibm.ibm_zos_core**: `v1.12.0`
- **ibm.ibm_zos_cics**: `v2.1.0`
- **ibm.ibm_zos_ims**: `v1.3.0`
- **ibm.ibm_zosmf**: `v1.5.0`

### **ServiceNow**
- **ibm.servicenow.itsm**: `v2.7.0`
- **servicenow.itsm**: `v2.7.0`

### **Amazon**
- **amazon.aws**: `v9.1.1`

### **Community**
- **community.general**: `v10.2.0`

### **Ansible Utils**
- **ansible.utils**: `v5.1.2`
