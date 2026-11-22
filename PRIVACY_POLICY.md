# Privacy Policy for ClashVista

**Effective Date:** November 2026  
**Publisher:** ABIR DAS  
**Application:** ClashVista (Autodesk App Store App ID: 1237288957200256437)  
**Contact:** abirdas.pinnacle@gmail.com  

---

### 1. Overview
ClashVista respects your privacy. **ClashVista** is a professional BIM & MEP coordination add-in designed to run locally within Autodesk® Revit®. This Privacy Policy outlines our data practices.

### 2. No Collection of BIM Models or Project Data
Clash Pilot operates entirely locally on your workstation:
- We do **NOT** collect, inspect, upload, store, or transmit any proprietary 3D BIM models, Revit project geometry (.rvt), family files (.rfa), drawings, or company design files.
- All spatial intersection calculations, clash detection analyses, category filtering, and report exports (Excel/PDF) are executed strictly in-memory on your local workstation.

### 3. Subscription & Entitlement Verification
To verify an active purchase or recurring subscription:
- The application queries the official Autodesk App Store Entitlement API:  
  `https://apps.autodesk.com/webservices/checkentitlement`
- Only the signed-in Autodesk User ID (provided by Revit API) and Application ID are transmitted to confirm active entitlement.
- For offline job-site resilience, valid tokens are cached locally with hardware encryption for up to 30 days.
- No payment credentials or passwords are ever accessed or stored by our app; transactions are processed entirely by Autodesk.

### 4. Third-Party Sharing
We do not sell, rent, trade, share, or disclose any user or company data with third parties.

### 5. Contact Us
For questions regarding this policy:  
- **Email:** abirdas.pinnacle@gmail.com  
- **Website:** https://github.com/abirdas459/ClashVista
