# VulManAgg
## Vulnerability management aggregation of AppSec &amp; OpSec (Tools Listing)

OpSec being primarily driven by scanning IP ranges or Invoking Cloud API's to inventory assets, this is normally tracked by (IP/DNS + Port + Issue).

Dynamic AppSec ordinarily starts by defining the application endpoint comprising of a (URL + PORT + URI) and once issues are identified this is appended to the defined application and tracked in this manner. Many of the assets found by OpSec scanning could be involved or even shared with other applications making tracking across these spheres more difficult.

Static AppSec defines the project and its dependant source code repositories and scans for logic flaws as BUGS, Vulnerabilities, SMELLS and measures test coverage and duplications, so again represent a different dataset in terms of the results generated, trying to map accross all these spheres is very challenging.

Trying to tie these spheres together should give a more holistic view of how vulnerable a particular project maybe and where one can prioritise efforts. It is not just a case of hoovering up the many different types of testing, but also various intel feeds with which one can enrich the dataset before finally issuing the normalised data out into the various tools developers and operational teams already have. Keeping track of these issues and any exceptions that may arise such as accepting risks is also another key area to judge any tool/platform that will assist in the vulnerability management workflow.

The following table is an initial list of tools that seek to aggregate such data to assist in streamlining the workflow.

|AppSec|OpSec|OSS|URL|Notes|
|---|---|---|---------------------------|--|
| Y | Y | N | https://www.kennasecurity.com/ |
| Y | Y | N | https://www.brinqa.com/ |
| Y | Y | N | https://www.nucleussec.com/ | 
|Y | N | N | https://threadfix.it/ | No longer OSS |
| Y | Y | N | https://www.netspi.com/resolve/ |
| Y | Y | Y | https://github.com/DefectDojo/django-DefectDojo | Looks the Biz but cannot import, '0 findings were processed' | 
| Y | Y*| Y | https://github.com/olacabs/jackhammer | Online demo has no import, cannot build any version locally |
| ? | ? | N | https://elastic-detector.secludit.com/home/sign_in |
| Y* | Y* | N | https://www.nopsec.com/ |
| ? | ? | Y&N | https://vfeed.io/ |
| Y | Y | Y | https://www.seccubus.com | * Not a tool to consolidate scan data |
| ? | Y | N | https://peoplesec.org/solutions/defects-analytics-portal/ |
| Y | N | N | https://software.microfocus.com/en-us/products/software-security-assurance-sdlc/overview |
| Y | ? | N | https://codedx.com/ |
| Y | Y | N | https://www.rapid7.com/products/insightvm/ |
| Y | Y* | Y* | https://archerysec.info/ | Lack of import options, seems oriented to built in tools |
| N* | N* | N | https://www.flexera.com/products/software-vulnerability-management/ |
| Y | Y | N | https://allgress.com/vulnerability-analysis |
| Y | Y | N | https://gauntlet.io/ |
| N | N | Y | https://www.talend.com/products/talend-open-studio/ | Can map and normalise many datasets |
| Y | ? | Y&N | https://www.faradaysec.com/ | CE edition heavily stripped back |
| Y | ? | Y&N | https://dradisframework.com/ | pentest & owasp oriented |
| Y | ? | Y | http://vulnreport.io/ | pentest & owasp oriented |
| Y | ? | ? | https://checksec.com/canopy.html |
| Y | Y | N | https://www.skyboxsecurity.com/products/skybox-vulnerability-control |
| ? | ? | ? | https://www.simplerisk.com/ | orientated towards risk audits |
| Y | Y | N | https://www.tenable.com/products/tenable-lumin | they plan to pull in 3rd party scan data one to watch |

#####  ToDo add supported inputs and outputs

### Want to make this better.
```Fork > Mod > Submit Pull Request ```
