# web232
use serial port to send print data to a zebra printer

The html use the StrokeReader ocx plugIn to communicate with the serial port.
Js call the send() function.

For compatible with firefox and chrome, need to install ffactivex-setup-r39.exe which use NPAPI to call the ocx.
Chrome is going to disable NPAPI after Chrome 45, so newer version chrome may not support the html file execute.

About the class, attributes, methord inside StrokeReader, the MicroSoft's VS include the COM/OLE viewer tool can help.
