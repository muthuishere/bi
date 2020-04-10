
{
"userName":"username",
"password":"password",
"auth":"secEnterprise"

}


Rest Api document


https://help.sap.com/doc/220244879d104f2e8e8b37e0fa0bdd2d/4.2.3/en-US/sbo42sp3_bip_rest_ws_en.pdf





Step 1 : Get logon token

Method : POST
URL : http://<server>:<port>/biprws/logon/long
Headers :
Accept:application/json
Content-Type:application/xml

Body:

<attrs xmlns="http://www.sap.com/rws/bip">
    <attr name="userName" type="string">userid</attr>
    <attr name="password" type="string">pwd</attr>
    <attr name="auth" type="string" possibilities="secEnterprise,secLDAP,secWinAD,secSAPR3">secEnterprise</attr>
</attrs>

Step 2: Get list of all universes

Method : GET
URL: http://<server>:<port>//biprws/raylight/v1/universes
Headers:
Content-Type:application/xml
Accept:application/xml
X-SAP-LogonToken:<token>

Step 3 : Get details of the universe
Method : GET
URL: http://<server>:<port>//biprws/raylight/v1/universes/<universeid>
Headers:
Content-Type:application/xml
Accept:application/xml
X-SAP-LogonToken:<token>



