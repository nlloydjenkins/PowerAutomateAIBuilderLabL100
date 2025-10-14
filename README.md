# Power Automate AI Builder Labs

This repository contains two hands-on labs that demonstrate how to build automated workflows using Microsoft Power Automate and AI Builder.

---

## Prerequisites

- Microsoft 365 account with Power Automate and AI Builder licenses
- AI Builder credits enabled in your environment
- Access to a SharePoint site where you can create document libraries and lists
- Permissions to create and edit flows, AI Builder models, and SharePoint resources

---

## Labs

### Lab 1: Invoice Processing with AI Builder

**File:** `Lab-1-Invoice-Processing-with-AI-Builder.md`

**Duration:** 45-60 minutes

This lab demonstrates how to automate invoice processing by extracting information from PDF invoices and storing it in SharePoint. The flow uses AI Builder's prebuilt invoice processing model and custom AI prompts to extract vendor information, invoice numbers, line items, and totals.

**Technologies used:**
- AI Builder prebuilt invoice processing model
- AI Builder custom prompts (GPT-based)
- SharePoint document library and list
- Power Automate variables and loops

---

### Lab 2: Custom Object Detection - Green Tea Detection

**File:** `Lab-2-Custom-Object-Detection-Green-Tea-Detection.md`

**Duration:** 60-90 minutes (includes model training time)

This lab shows how to create a custom AI Builder object detection model to identify green tea products in images. You'll train the model with sample images, then build a flow that analyzes uploaded images and logs detection results to SharePoint.

**Technologies used:**
- AI Builder custom object detection model
- Model training and image tagging
- SharePoint image library and list
- Power Automate conditions and loops
- Office 365 Outlook for notifications

---

## Sample Files

The repository includes sample files for testing:

- **Invoices/** - Sample invoice PDFs (Adatum and Contoso companies) for Lab 1
- **Green Tea/Train/** - Training images (30+ images) for Lab 2 model training
- **Green Tea/Test/** - Test images (16 images) for Lab 2 model validation
- **Solution/** - Pre-built solution package for Lab 1 (`ProcessInvoice_20251010105827.zip`)

---

## Repository Structure

```
PowerAutomateAIBuilderLabL100/
├── README.md
├── Lab-1-Invoice-Processing-with-AI-Builder.md
├── Lab-1-Invoice-Processing-with-AI-Builder.pdf
├── Lab-2-Custom-Object-Detection-Green-Tea-Detection.md
├── Lab-2-Custom-Object-Detection-Green-Tea-Detection.pdf
├── Invoices/                  # Sample invoice PDFs
├── Green Tea/
│   ├── Train/                 # Training images
│   └── Test/                  # Test images
├── screenshots/               # Lab reference screenshots
└── Solution/                  # Pre-built solution package
```

---

## Additional Resources

- [Power Automate Documentation](https://learn.microsoft.com/power-automate/)
- [AI Builder Documentation](https://learn.microsoft.com/ai-builder/)
- [SharePoint Connector Reference](https://learn.microsoft.com/connectors/sharepointonline/)


