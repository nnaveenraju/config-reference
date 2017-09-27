# config-reference
config-reference


Mulerequester for SFTP:

<mulerequester:request 
        resource="sftp://${sftp.uname}:${sftp.pass}@${sftp.host}${msu.sftp.incoming.path}?connector=SFTP" 
        doc:name="Mule Requester" 
        throwExceptionOnTimeout="true"/>


Mulerequester for reading from VM:

<mulerequester:request-collection 
        resource="vm://dlq_sf_data?connector=VM" 
        doc:name="Mule Requester"/>
