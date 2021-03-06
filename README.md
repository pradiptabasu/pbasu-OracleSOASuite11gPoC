# pbasu-OracleSOASuite11gPoC


# JDeveloper Updates, SOA, BPM, AIA updates
* https://www.oracle.com/ocom/groups/public/@otn/documents/webcontent/156082.xml
* https://www.oracle.com/ocom/groups/public/@otn/documents/webcontent/131167.xml
* https://www.oracle.com/ocom/groups/public/@otn/documents/webcontent/130355.xml



# Export and Setup File based MDS
* http://markchensblog.blogspot.com/2011/08/oracle-soa-mds.html
* http://prabhasoablog.blogspot.com/2018/03/how-to-importexportdeploy-mds-from-em.html

# Import, Export, Delete Files from MDS
* https://rathinasaba.wordpress.com/2012/08/16/import-export-delete-files-from-mds/
* http://inside-bpm-and-soa.blogspot.com/2013/08/remove-data-in-oracle-mds.html
* https://docs.oracle.com/cd/E28280_01/dev.1111/e10224/sca_lifecycle.htm
* http://oraclesoa.blogspot.com/2011/07/how-to-remove-contents-from-mds.html
* http://diveintomiddleware.blogspot.com/2015/04/oracle-soa-how-to-clean-remove-contents_23.html
* https://community.oracle.com/thread/1262814?start=15&tstart=0
* http://prabhasoablog.blogspot.com/2018/01/delete-files-and-folders-from-MDS.html
* http://oraclesoasolution.blogspot.com/2016/11/steps-to-delete-data-from-mds-soa-inrfa.html
* http://talksoa.blogspot.com/2015/09/removing-files-folders-from-soa-mds.html
* http://oraclesoaandoim.blogspot.com/2017/02/soa-12c-how-to-remove-folder-and-files.html
* https://khassoablog.wordpress.com/2016/04/23/removing-unused-files-from-oracle-soa-suite-mds/
* http://www.ateam-oracle.com/working-with-deployment-plans
* http://manojm-nair.blogspot.com/2013/04/
* https://gist.github.com/biemond/1248843
* http://yuanmengblog.blogspot.com/2013/02/wlst-and-mds.html
* 
* 
* 
* 

# SOA 11g REST JSON Kafka
* https://technology.amis.nl/2009/12/15/the-oracle-soa-suite-11g-httpbinding-or-another-way-to-call-restful-services-from-soa-composite-applications/
* http://sridhar-oraclefusion.blogspot.com/2014/08/calling-rest-service-methods-with-json.html
* 
* 

# XREF Lookup
* https://rathinasaba.wordpress.com/tag/xref-lookup-function/

select * from DEV_SOAINFRA.XREF_DATA
WHERE XREF_COLUMN_NAME = 'NGCRM'
AND VALUE = '<SIEBEL_ID>'

select * from DEV_SOAINFRA.XREF_DATA
WHERE XREF_COLUMN_NAME = 'Siebel' 
AND VALUE = '<SIEBEL_ID>'

select * from DEV_SOAINFRA.XREF_DATA
WHERE XREF_COLUMN_NAME = 'COMMON'
AND VALUE = (	select ROW_NUMBER from DEV_SOAINFRA.XREF_DATA
				WHERE XREF_COLUMN_NAME = 'NGCRM'
				AND VALUE = '<SIEBEL_ID>' )


# using CDATA
* https://jvzoggel.com/2011/02/17/using-cdata-in-the-oracle-service-bus/
* OSB and CDATA Section Handling (Doc ID 1448669.1)
* OSB CDATA Section is Being Stripped (Doc ID 2425704.1)
* http://rohanlopes.blogspot.com/2011/10/passing-cdata-in-xquery-using-osb.html
* http://jaredsoablogaz.blogspot.com/2013/04/using-cdata-to-handle-embedded-xml.html
* https://archenroot.wordpress.com/2015/02/15/using-cdata-in-the-oracle-service-bus/
* https://khassoablog.wordpress.com/2016/02/20/capture-the-result-in-cdata-format-in-osb/
* http://markchensblog.blogspot.com/2012/06/use-cdata-to-pass-symbol-to-bpel-osb.html
* https://soachamp.wordpress.com/2015/06/17/transformation-of-string-to-xml-or-xml-to-string-oracle-osb/
* https://github.com/kamesh46/KameshOSBProject/tree/master/StringToXMLConversion
* https://community.oracle.com/thread/1105672
* SOA 11g: ORA:TOCDATA() Function Creates CDATA Syntax which is Stripped from the BPEL Payload (Doc ID 1501568.1)
* https://cloudcustomerconnect.oracle.com/posts/a7f2d5a9e8?commentId=104291#104291
* https://llorllale.github.io/embedding-cdata-section-in-your-bpel/
* https://llorllale.blogspot.com/2013/03/embedding-cdata-section-in-your-bpel.html
* 
* 
* 
* 
* 
* 
* 
* 
* 
