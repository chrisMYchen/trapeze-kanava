# Call Routing Guide - Coastal Eye

## Overview
This document serves as a comprehensive routing guide for the AI call receptionist system at Coastal Eye. It integrates information from appointment types, vision correction options, service rates, and insurance participation to effectively route callers to the appropriate resources.

## Provider Specialization & Availability

### Dr. Omar Perdomo, OD (Optometrist)
- **Specializes In**: Primary eye care, contact lens fittings, ocular surface disease
- **Handles**: 
  - Comprehensive eye exams
  - Contact lens fittings
  - Glasses prescriptions
  - Minor eye conditions (dry eye, conjunctivitis, etc.)
  - Visual field interpretation

### Dr. Omar Razzique Shakir, MD, MBA (Ophthalmologist)
- **Specializes In**: Cataract and Vitreoretinal Surgery
- **Handles**:
  - Cataract evaluations and surgery
  - Refractive Lens Exchange (RLE)
  - EVO ICL implantation
  - Floater removal (PPV)
  - Retinal conditions and treatments
  - Specialized eye injections
  - Laser procedures

### Second Optometrist
- **Handles**: Similar services to Dr. Perdomo
  - Comprehensive eye exams
  - Contact lens fittings
  - Glasses prescriptions
  - Minor eye conditions

## Call Routing Decision Tree

### 1. New Patient Calls
- **For routine eye exam or glasses/contacts needs**:
  - Route to scheduling with Dr. Perdomo or Second Optometrist
  - Collect: Full name, DOB, contact info, insurance details
  - Remind: Send insurance card photos to Weave

- **For cataract concerns**:
  - Route to scheduling with Dr. Shakir (Surgical Consult - 30 mins)
  - Request medical records from previous provider
  - Collect insurance information
  
- **For vision correction inquiries**:
  - If patient is 18-45 years old → Mention EVO ICL option and schedule consultation with Dr. Shakir
  - If patient is 45-65 years old → Mention RLE option and schedule consultation with Dr. Shakir
  - If patient mentions LASIK → Explain that Coastal Eye offers advanced alternatives to LASIK
  
- **For eye pain or emergency concerns**:
  - Determine severity (see Emergency Triage section below)
  - Route urgent cases to same-day appointments when available
  
### 2. Established Patient Calls
- **For follow-up appointments**:
  - Schedule with the provider who performed their initial exam
  - Check for specific follow-up timeframe in patient notes
  
- **For prescription renewals**:
  - Verify when patient was last seen (must be within 1 year)
  - If due for exam, schedule appointment
  
- **For post-surgical follow-ups**:
  - Schedule with Dr. Shakir according to post-op protocol

### 3. Insurance & Billing Inquiries
- **For insurance verification**:
  - Confirm Coastal Eye participates with their plan using Insurance Participation list
  - For plans not on list, advise caller to check with their insurance
  - Remind: We do NOT participate with ANY vision plans

- **For cost inquiries**:
  - Provide information from Service Rates document
  - For RLE pricing, transfer to Jackie
  - Remind caller that refraction fee ($80) is typically not covered by insurance

### 4. Special Procedure Inquiries
- **For laser procedures**:
  - Route to scheduling with Dr. Shakir (Wednesdays only)
  
- **For eye injections**:
  - Route to scheduling with Dr. Shakir (Monday, Tuesday, Thursday)
  - If scheduling within a few days, notify Lori
  
- **For Visual Field testing**:
  - Schedule as standalone appointment or with provider follow-up
  - Remind patient to bring glasses/contacts
  
- **For IOL Master measurements**:
  - Schedule 1-2 weeks before planned cataract surgery
  - 30-minute appointment

## Emergency Triage Guidelines

### Immediate Transfer to Staff (Emergency Conditions)
- Sudden vision loss
- Eye trauma/injury
- Chemical exposure to eye
- Severe eye pain
- Flashes of light with many new floaters (possible retinal detachment)

### Same-Day Appointment Needed
- Foreign body sensation
- New onset of double vision
- Eye infection with discharge
- Significant eye redness with pain

### Can Wait 1-3 Days
- Mild eye irritation
- Gradual increase in floaters without flashes
- Minor eye strain or discomfort
- Slight blurring of vision without other symptoms

## Common Routing Scenarios

### Scenario 1: Cataract Patient Pathway
1. Patient calls about blurry vision, mentions "hazy" or "cloudy" sight
2. Schedule Surgical Consult with Dr. Shakir (30 mins)
3. Mention that Coastal Eye offers advanced LAL+ technology
4. Verify insurance and request previous medical records
5. After consultation, surgical coordinator (Bryan) handles surgery scheduling

### Scenario 2: Contact Lens Patient Pathway
1. Patient calls for contact lens fitting
2. Schedule with Dr. Perdomo or Second Optometrist
3. Mention $150 contact lens fitting fee (often not covered by insurance)
4. Verify insurance for comprehensive exam portion coverage

### Scenario 3: Diabetic Eye Exam Pathway
1. Patient mentions diabetes and need for eye exam
2. Schedule comprehensive exam with Dr. Perdomo or Second Optometrist
3. Note in appointment that patient needs dilated diabetic eye exam
4. Verify medical insurance (typically covered as medical necessity)

### Scenario 4: Retinal Injection Patient
1. Established patient calls for regular eye injection
2. Verify which medication (Eylea, Lucentis, Avastin, etc.)
3. Schedule with Dr. Shakir (Monday, Tuesday, or Thursday)
4. If urgent or short notice, notify Lori to check medication stock

## Transfer Guidelines
- **When to transfer to human staff immediately**:
  - Medical emergencies
  - Billing disputes
  - Surgical scheduling questions
  - Complex insurance situations
  - When AI cannot confidently answer specific medical questions
  - RLE pricing inquiries (transfer to Jackie)
  - Surgery scheduling (transfer to Bryan)
  
## Privacy Reminder
- Never discuss specific patient medical information
- Verify caller identity before sharing any patient information
- Do not access or reference EHR system
- Only use information provided during the current call