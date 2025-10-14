# Power Automate AI Builder Labs - Level 100

Welcome to the Power Automate AI Builder hands-on labs! This repository contains two comprehensive labs designed to help you learn how to build intelligent automation solutions using Microsoft Power Automate and AI Builder.

---

## Overview

These labs are designed for beginners (Level 100) and provide step-by-step instructions to create automated workflows that leverage AI capabilities. No prior experience with AI Builder is required.

### What You'll Learn

- How to create automated flows in Power Automate
- How to use AI Builder's prebuilt and custom models
- How to integrate AI capabilities with SharePoint
- How to process documents and detect objects using AI
- Best practices for building production-ready automation

---

## Prerequisites

Before starting these labs, ensure you have:

- **Microsoft 365 account** with Power Automate and AI Builder licenses
- **AI Builder credits** enabled in your environment
- **Access to a SharePoint site** where you can create document libraries and lists
- **Permissions** to create and edit flows, AI Builder models, and SharePoint resources
- **Sample files** for testing (included in this repository)
- **Basic understanding** of SharePoint and Power Automate navigation

---

## Lab Descriptions

### Lab 1: Invoice Processing with AI Builder

**File:** `Lab-1-Invoice-Processing-with-AI-Builder.md`

**Duration:** ~45-60 minutes

**Scenario:** Automate invoice processing by extracting key information from PDF invoices and storing the data in SharePoint.

#### What You'll Build

A Power Automate flow that:
1. Triggers when an invoice PDF is uploaded to SharePoint
2. Extracts invoice data using AI Builder's prebuilt invoice processing model
3. Processes line items using custom AI prompts
4. Categorizes products intelligently
5. Creates structured records in a SharePoint list

#### Key Technologies

- **AI Builder Prebuilt Model:** Invoice processing
- **AI Builder Custom Prompts:** GPT-based text generation
- **SharePoint Connector:** Document library and list integration
- **Variables & Loops:** Data processing and transformation

#### Skills Covered

- Working with AI Builder prebuilt models
- Creating and using custom AI prompts
- Processing dynamic collections with loops
- Mapping complex data structures
- Error handling and troubleshooting

---

### Lab 2: Custom Object Detection - Green Tea Detection

**File:** `Lab-2-Custom-Object-Detection-Green-Tea-Detection.md`

**Duration:** ~60-90 minutes (includes model training time)

**Scenario:** Build a custom AI model to detect green tea products in images and automatically log detection results.

#### What You'll Build

1. A custom AI Builder object detection model trained to recognize green tea products
2. A Power Automate flow that:
   - Triggers when a product image is uploaded to SharePoint
   - Analyzes the image using your custom AI model
   - Detects and counts green tea products
   - Logs detection results with confidence scores
   - Sends notifications based on detection outcomes

#### Key Technologies

- **AI Builder Custom Model:** Object detection
- **Model Training:** Image tagging and training
- **SharePoint Connector:** Image storage and results tracking
- **Conditions & Loops:** Smart decision-making and batch processing
- **Email Notifications:** Office 365 Outlook connector

#### Skills Covered

- Creating custom AI Builder models
- Training object detection models
- Image tagging and annotation
- Working with AI confidence scores
- Implementing conditional logic
- Building notification systems

---

## Getting Started

### Step 1: Choose Your Lab

- **New to AI Builder?** Start with **Lab 1** to learn the basics with a prebuilt model
- **Want to build custom AI?** Jump to **Lab 2** to create your own object detection model
- **Best learning path:** Complete both labs in order (Lab 1 → Lab 2)

### Step 2: Review Prerequisites

1. Ensure you have all required licenses and permissions
2. Verify AI Builder credits are available in your environment
3. Set up a SharePoint site for testing (or use an existing one)

### Step 3: Gather Sample Files

Sample files are included in this repository:
- **Invoice PDFs** - Located in the `Invoices/` folder for Lab 1 testing
- **Green Tea product images** - Located in the `Green Tea/Train/` folder for Lab 2 training
- **Test images** - Located in the `Green Tea/Test/` folder for Lab 2 testing

### Step 4: Follow the Lab Instructions

Each lab includes:
- Detailed step-by-step instructions
- Screenshot placeholders showing what to expect
- Tips and best practices
- Troubleshooting guidance
- Optional enhancements to extend your learning

---

## Repository Structure

```
PowerAutomateAIBuilderLabL100/
├── README.md                                           # This file - repository overview
├── Lab-1-Invoice-Processing-with-AI-Builder.md        # Lab 1: Invoice Processing guide
├── Lab-1-Invoice-Processing-with-AI-Builder.pdf       # Lab 1: PDF version
├── Lab-2-Custom-Object-Detection-Green-Tea-Detection.md # Lab 2: Object Detection guide
├── Lab-2-Custom-Object-Detection-Green-Tea-Detection.pdf # Lab 2: PDF version
├── Invoices/                                           # Sample invoice PDFs for Lab 1
│   ├── Adatum 1-5.pdf
│   └── Contoso 1-5.pdf
├── Green Tea/                                          # Green tea product images for Lab 2
│   ├── Train/                                          # Training images (30+ images)
│   └── Test/                                           # Test images (16 images)
├── screenshots/                                        # Lab screenshots for reference
├── Solution/                                           # Pre-built solution package
│   └── ProcessInvoice_20251010105827.zip
└── image files                                         # Various reference images
```

---

## Tips for Success

### General Tips

- **Take your time:** These labs are designed to be educational, not a race
- **Read carefully:** Pay attention to field names and dynamic content selections
- **Save frequently:** Save your flow after completing each major section
- **Test incrementally:** Use the flow checker and test after each section
- **Use screenshots:** Compare your work with the screenshots provided in each lab
- **Unique names:** In shared environments, prefix your resources with your initials to avoid conflicts
- **Designer versions:** Instructions include notes for both classic and new Power Automate designers

### AI Builder Tips

- **Check your credits:** AI Builder operations consume credits - verify you have credits available
- **Monitor usage:** Keep an eye on your AI Builder credit consumption in the Power Platform admin center
- **Model quality:** For Lab 2, better training data = better detection accuracy (minimum 15-50 images per object)
- **Confidence scores:** Understand that AI predictions include confidence levels (typically 0.5-0.8 is good)
- **Training time:** Custom models (Lab 2) can take several minutes to an hour to train
- **Model publishing:** Always publish your AI Builder models before using them in flows

### Troubleshooting

- **Flow doesn't trigger?** Verify you're uploading files to the correct SharePoint library
- **Flow errors?** Check the flow run history for detailed error messages
- **Connection issues?** Verify all connectors are properly authenticated
- **AI Builder errors?** Ensure your models are published and in the same environment
- **Dynamic content missing?** Make sure previous steps ran successfully
- **Variable errors?** Ensure you're selecting from Dynamic content, not typing manually
- **Custom prompts failing?** Verify prompts are saved and inputs are correctly mapped
- **Detailed troubleshooting:** Each lab includes a comprehensive Troubleshooting section

---

## Learning Outcomes

After completing these labs, you will be able to:

- Create automated workflows in Power Automate  
- Integrate AI Builder models into your flows  
- Use prebuilt AI models for document processing  
- Build and train custom AI models for object detection  
- Work with SharePoint connectors for data storage  
- Implement conditional logic and loops  
- Handle dynamic content and expressions  
- Test and troubleshoot Power Automate flows  
- Apply best practices for production automation  

---

## Additional Resources

### Microsoft Documentation

- [Power Automate Documentation](https://learn.microsoft.com/power-automate/)
- [AI Builder Documentation](https://learn.microsoft.com/ai-builder/)
- [SharePoint Connector Reference](https://learn.microsoft.com/connectors/sharepointonline/)

### Community Resources

- [Power Automate Community](https://powerusers.microsoft.com/t5/Microsoft-Power-Automate/ct-p/MPACommunity)
- [AI Builder Community](https://powerusers.microsoft.com/t5/AI-Builder/bd-p/AIBuilder)

### Training & Certifications

- [Microsoft Learn: Power Automate Learning Paths](https://learn.microsoft.com/training/browse/?products=power-automate)
- [Microsoft Learn: AI Builder Learning Paths](https://learn.microsoft.com/training/browse/?products=ai-builder)

---

## What's New

- **Updated screenshots:** All images now organized in the `screenshots/` folder with descriptive names
- **Enhanced troubleshooting:** Both labs include comprehensive troubleshooting sections
- **Designer compatibility:** Instructions include notes for both classic and new Power Automate designers
- **Pre-built solution:** Lab 1 solution package available in the `Solution/` folder

---

## Contributing

Found an issue or have suggestions for improvement? Contributions are welcome!

---

## License

This project is provided as-is for educational purposes.

---

## Support

If you encounter issues while working through these labs:

1. Check the **Troubleshooting** section in each lab document
2. Review the flow run history for detailed error messages
3. Consult the Microsoft documentation linked above
4. Reach out to the Power Automate community

---

**Happy Learning!**

Build intelligent automation solutions with Power Automate and AI Builder!
