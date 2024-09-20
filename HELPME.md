1. How to run:
   + Application run as debug
   - gradle build -x test
   - in git bash ./gradlew build -x test
   - 
3. post http://localhost:8080/service/student-details
"Content-Type:text/xml":
```
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:sch="https://www.howtodoinjava.com/xml/school">
   <soapenv:Header/>
   <soapenv:Body>
      <sch:StudentDetailsRequest>
         <sch:name>Sajal</sch:name>
      </sch:StudentDetailsRequest>
   </soapenv:Body>
</soapenv:Envelope>



