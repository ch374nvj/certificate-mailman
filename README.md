# certificate-mailman
A simple script written in python, that would take in a certificate template made in an illustrator of your choice, a csv dataset consisting of the participants, their attendance, and their email. 
The current script is such that, It checks if a certain team was present at venue, creates a folder in their email id, and generate PDF files of the respective participants' certificates.
The other part of the code, parses these folders, prepares an email body using the mail template, attaches the PDF certificates and sends them to respective mail id. Depending on PC specs, and internet speed, each mail takes at most 30s to prepare and send, while only the certificates takes 10s per item.

This very piece of software was used to distribute the certificates to over 250+ participants of technotsav-2k24
