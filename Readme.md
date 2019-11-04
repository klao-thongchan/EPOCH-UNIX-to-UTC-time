EPOCH = UNIX timestamp showing as a number such as 1572838239
meaning Mon, 04 Nov 2019 03:30:28 GMT in Human date

website we normally use to convert: https://www.epochconverter.com/

EXCEL formula (refer to cell A1)

UNIX to Human
=(((A1/60)/60)/24)+DATE(1970,1,1)

Human to UNIX
=(A1-DATE(1970,1,1))*86400

