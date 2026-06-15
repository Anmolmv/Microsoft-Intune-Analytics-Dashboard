# Microsoft-Intune-Analytics-Dashboard
Power BI dashboard integrating Microsoft Intune data using Microsoft Graph APIs for device inventory, compliance, OS analytics, and endpoint visibility.

# Microsoft Intune Analytics Dashboard

## Project Overview

This project demonstrates how Microsoft Intune data can be integrated with Power BI using Microsoft Graph APIs to provide centralized visibility into managed devices, compliance posture, operating system distribution, and endpoint analytics.

The solution enables IT administrators and stakeholders to monitor device health, compliance status, and inventory information through an interactive dashboard.

---

## Business Objective

Organizations often struggle to obtain a centralized view of endpoint devices managed through Microsoft Intune.

This solution provides:

- Device Inventory Visibility
- Compliance Monitoring
- OS Distribution Analytics
- Endpoint Health Insights
- Device Synchronization Tracking

---

## Architecture

Managed Devices
↓
Microsoft Intune
↓
Microsoft Graph API
↓
Power BI
↓
Scheduled Refresh Dashboard

---

## Technologies Used

- Microsoft Intune
- Microsoft Graph API
- Microsoft Entra ID
- Power BI
- Power Query
- REST APIs

---

## Key Dashboard KPIs

### Device Inventory

- Total Managed Devices
- Active Devices
- Device Manufacturers
- Device Models

### Compliance Analytics

- Compliance Percentage
- Non-Compliant Devices
- Stale Devices

### OS Analytics

- Windows Devices
- macOS Devices
- Android Devices
- iOS Devices

### Device Health

- Last Synchronization
- Device Activity Monitoring
- Endpoint Visibility

---

## Graph API Endpoints

### Managed Devices

GET /deviceManagement/managedDevices

### Device Compliance

GET /deviceManagement/deviceCompliancePolicies

### Endpoint Analytics

GET /deviceManagement/userExperienceAnalyticsOverview

### Audit Logs

GET /deviceManagement/auditEvents

---

## Future Enhancements

- Scheduled Refresh Optimization
- Historical Trend Analysis
- Sentinel Integration
- OneLake Integration
- Advanced Endpoint Analytics

---

## Author

Anmol George

Master's in Data & Business Analytics

Power BI | Data Analytics | Microsoft Technologies
