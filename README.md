# PROG101-ASSIGNMENT1-ANITA-VERONICA-SAMSUMANA-905006548
Is Assignment 1 for programing logic and design about a maternal healthcare app designed mainly for pregnant women

## 1.1 problem identification
• Missed appointments: Families often forget antenatal or follow-up visits; there is no simple reminder system
• Fragmented records: Patient information is mostly paper-based easily lost, damaged, or unavailable when a patient visits a different facility
• Poor referrals: When a clinic cannot help a patient, referrals are often handwritten, delayed, or never arrive at the destination facility
• Limited awareness: Many families do not recognise early danger signs in pregnancy or childhood illness until a condition becomes serious
• Connectivity barriers: Internet access is unreliable or unavailable in most rural areas, making standard cloud-based applications impractical
• Emergency response gaps: There is no simple way to request emergency transport or assistance from remote locations

### People Affected
• Pregnant women and newborns the highest-risk groups
• Community Health Workers (CHWs) working in villages with limited tools
• Healthcare staff at clinics and hospitals managing without shared patient information
• Rural communities facing the longest travel times and poorest access
• Families making difficult decisions without clear guidance

#### Proposed Solution
Ensures continuous care from pregnancy through the first year of life, even in remote villages. CHWs can intervene early, and critical data follows the patient across facilities 
eliminating lost records during transfers or home births.
Converts unpredictable, large emergency expenses into affordable, incremental savings. It removes the heartbreaking choice between seeking care and meeting basic household needs.
Every healthcare provider has the full, accurate picture they need, right when they need it. This reduces medical errors, avoids repeated tests, and saves precious minutes during labour or acute illness.
Paper-based health records in Sierra Leone are frequently lost, damaged, or left at a different facility especially during emergencies or patient transfers.

 ##### Pseudocode 
 BEGIN
        Open SL PREG CARE
        IF user is not registered THEN
       Register user
      ENDIF
      Login user
       IF internet is available THEN
      Set Mode = Online
     ELSE
      Set Mode = Offline
       ENDIF
    Display Dashboard
    REPEAT
      User selects option
      CASE option OF
      Pregnancy Tracker:
            Save pregnancy information
            Schedule ANC reminders
            Check for danger signs
            IF danger signs detected THEN
                  Notify Community Health Worker
            ENDIF
      Symptom Checker:
            Ask symptom questions
            Analyse symptoms
            IF emergency THEN
                  Show Emergency Alert
            ELSE
                  Recommend clinic or home care
            ENDIF

      Teleconsultation:
            IF Online THEN
                  Connect doctor
            ELSE
                  Queue consultation request
            ENDIF
      Health Wallet:
            Deposit through Orange Money or Afrimoney
      Medical Records:
            Save or retrieve patient records
      Emergency:
            Send ambulance request
            Notify healthcare workers
      END CASE
      IF network becomes available THEN
            Sync local data with cloud
      ENDIF
       UNTIL user exits
 END  

 ###### screenshot
