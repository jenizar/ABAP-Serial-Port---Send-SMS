# ABAP-Serial-Port---Send-SMS
SAP ABAP Serial Port - Send SMS
Send message (SMS) to cell phone/modem in ABAP Z Program
Step by step:
1. Create ABAP Z Program
2. AT COMMAND sequence : 
AT+CSCS="GSM"
AT+CMGF=1
AT+CMGS="+628561811XXX" <message> <Ctrl+Z>

Note: 
1. Please close Putty apps while you test AT COMMAND in the ABAP Z program.
2. <Ctrl+Z> -> ASCII = 1A (Convert Hex to ASCII)

Reference:
1. https://blogs.sap.com/2013/07/10/read-comm-port-using-abap-wo-third-party-software/
2. https://blogs.sap.com/2014/10/02/how-to-registeractivate-activex-component-mscomm32ocx-on-windows-7/
3. https://avtech.com/articles/65/how-to-test-a-gsm-modem-manually/
