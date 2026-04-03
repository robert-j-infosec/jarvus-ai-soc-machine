# **Jarvus Prototype — Security Event Monitoring Demo**
A lightweight security monitoring prototype demonstrating log ingestion, event processing, and a clean web dashboard for reviewing system activity.

This project was built as a **technical showcase** to demonstrate practical skills in:

- Python backend development  
- Log parsing and normalization  
- Security event handling  
- Database design  
- Web UI development  
- Linux system interaction  
- End‑to‑end prototype engineering  

It is **not** a commercial product and does **not** include any proprietary detection logic or business‑specific components.

---

## **What This Prototype Demonstrates**
This project highlights the ability to build a functional security monitoring workflow from scratch:

### **✔ Log Ingestion**
- Reads Linux authentication logs (`/var/log/auth.log`)
- Extracts relevant security events
- Normalizes fields for consistent storage

### **✔ Event Processing**
- Identifies common authentication‑related patterns  
- Generates structured event records  
- Assigns simple severity levels  
- Supports optional MITRE ATT&CK tagging (non‑proprietary)

### **✔ Local Storage**
- SQLite database for portability  
- Simple schema for storing incidents  
- Fast local querying  

### **✔ Web Dashboard**
- Flask‑based interface  
- Bootstrap‑styled table  
- Severity badges  
- Clean, responsive layout  
- Custom hero section with branding  

### **✔ Frontend/UI Work**
- Custom CSS  
- Responsive design  
- Animated hero section  

---

## **Project Structure**
```
project/
│
├── app.py                 # Flask web application
├── parser.py              # Log ingestion + event processing
├── database.py            # SQLite helpers
│
├── static/
│   ├── style.css
│   ├── jarvus-logo.png
│   └── favicon.ico
│
└── templates/
    ├── base.html
    └── incidents.html
```

---

## **Skills Demonstrated**
This prototype showcases hands‑on experience with:

### **Backend Engineering**
- Python (Flask)
- File monitoring
- Parsing unstructured log data
- Data normalization
- Error handling and pipeline design

### **Security Concepts**
- Authentication event analysis  
- Basic severity classification  
- MITRE ATT&CK familiarity  
- Host‑based monitoring fundamentals  

### **Database Work**
- Schema design  
- Query optimization  
- Lightweight storage solutions  

### **Frontend/UI**
- HTML templating (Jinja2)
- Bootstrap 5
- Custom CSS animations
- Responsive layout design

### **Linux & Systems**
- Working with system logs  
- Understanding auth mechanisms  
- Running services on Ubuntu Server  

---

## **Installation**
### Requirements
- Python 3.10+
- Linux environment with access to system logs

### Setup
```bash
pip install -r requirements.txt
python app.py
```

Then open:

```
http://localhost:5000/incidents
```

---

## **Important Notes**
- This is a **technical demonstration**, not a production system.  
- No proprietary detection logic, models, or business‑specific components are included.  
- The purpose is to showcase engineering ability, not to represent a final product.  

---

## **Author**
Robert  
Houston, TX  
Security Engineering & SOC Operation
