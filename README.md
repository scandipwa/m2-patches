# Magento module: ScandiPWA_M2Patches

Provides a patch for following issues:
- email sending issue - when sending Email via SES AWS service an error appears: `554 Transaction failed: Expected disposition, got =.` (Fixed in magento version 2.3.5.)
- cron issue - the message que waits for messages forever 
