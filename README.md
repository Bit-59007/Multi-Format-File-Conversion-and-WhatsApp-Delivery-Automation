## Multi-Format File Conversion and WhatsApp Delivery Automation

### Overview
This workflow automates the process of converting files between multiple formats and delivering the converted files to users through WhatsApp. It supports different file conversion scenarios using API integrations and conditional logic to determine the appropriate conversion pathway.

### Workflow Architecture

Form Submission → Pathways/Switch → File Conversion API → File Upload → Database Record → Merge → WhatsApp Sender

### Supported File Conversions

- XLSX to PDF
- DOCX to PDF
- PDF to DOCX
- PDF to TXT

### Workflow Steps

1. Form Submission Trigger  
   - The workflow starts when a user uploads a file using a form.

2. Pathways / Switch Node  
   - The system checks the file type.
   - Based on the file format, the workflow routes the request to the correct conversion process.

3. File Conversion API  
   - The selected API converts the file into the required format.

4. File Upload  
   - The converted file is uploaded to cloud storage (e.g., Google Drive).

5. Create Record  
   - A record of the conversion is saved in a database (e.g., Airtable).

6. Merge Node  
   - All pathways are merged into a single output stream.

7. WhatsApp Sender  
   - The converted file is automatically sent to the user via WhatsApp.

### Key Features

- Multi-format file conversion automation
- Conditional workflow routing
- API-based file processing
- Cloud file storage integration
- Database logging of conversions
- Automated WhatsApp file delivery
- Scalable workflow architecture

### Use Cases

- Document format conversion services
- Automated file processing systems
- Business document management
- Student assignment conversion
- Office file automation
- Customer file delivery systems

### Technologies Used

- HTTP API Integration
- File Conversion APIs
- Google Drive
- Airtable Database
- WhatsApp Messaging API
- Workflow Automation Platform

### Skills Demonstrated

- Workflow Automation Design
- API Integration
- Conditional Logic Implementation
- File Processing Automation
- Cloud Storage Integration
- Messaging System Automation
- End-to-End System Design

  ### Screenshot
  <img width="1501" height="643" alt="image" src="https://github.com/user-attachments/assets/73e80bff-01dd-4592-b0f8-707d2bf8d986" />
