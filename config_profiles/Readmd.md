Download the file and run the following command to get it into a readble format:

security cms -D -i ${SIGNED_MOBILCONFIG} | xmllint --format - > ${CLEAR_XML}.mobileconfig
